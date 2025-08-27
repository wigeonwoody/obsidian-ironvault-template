<%*
let originalName = tp.file.title;
let truncated = originalName.slice(0, 30); // Adjust length
let newName = truncated + (originalName.length > 30 ? "…" : "");
await tp.file.rename(newName);
%>
