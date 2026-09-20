<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cuu9-1duc"/><path class="uyb4qvihi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-shell" /></template>
<style>
.cuu9-1duc {
  fill: var(--svg-color--d9b400, #d9b400);
  d: path("M29.4 27.6H2.5V4.5h26.9Zm-25.9-1h24.9V5.5H3.5Z");
}

.uyb4qvihi {
  fill: var(--svg-color--d9b400, #d9b400);
  d: path("m6.077 19.316l-.555-.832l4.844-3.229l-4.887-4.071l.641-.768l5.915 4.928zM12.7 18.2h7.8v1h-7.8zM2.5 5.5h26.9v1.9H2.5z");
}

</style>
