<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iicx13b3r"/><path class="oqiqno76k"/><path class="n3wxoacoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-yarn-opened" /></template>
<style>
.iicx13b3r {
  fill: var(--svg-color--7abddc, #7abddc);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.n3wxoacoi {
  fill: var(--svg-color--2188b6, #2188b6);
  d: path("M30.42 26.27a5.2 5.2 0 0 0-2 .91a11.7 11.7 0 0 1-2.91 1.32a.82.82 0 0 1-.49.28a32 32 0 0 1-3.22.29c-.58 0-.94-.15-1-.39a.78.78 0 0 1 .41-1a1.6 1.6 0 0 1-.26-.19c-.08-.08-.17-.25-.2-.19c-.11.27-.17.95-.47 1.25a1.51 1.51 0 0 1-1.66 0c-.51-.28 0-.91 0-.91a.36.36 0 0 1-.49-.16a2.5 2.5 0 0 1-.29-1.48a2.68 2.68 0 0 1 .88-1.44a4.6 4.6 0 0 1 .33-2.2a5.2 5.2 0 0 1 1.57-1.84s-1-1.07-.6-2c.23-.63.33-.63.4-.66a1.8 1.8 0 0 0 .73-.43a2.64 2.64 0 0 1 2.2-.85s.58-1.77 1.12-1.43a9.6 9.6 0 0 1 .77 1.45s.63-.38.71-.24a5.83 5.83 0 0 1 .26 3.07a7 7 0 0 1-1.3 2.7A5.8 5.8 0 0 1 26.22 24a5.7 5.7 0 0 1 .13 2.6a3.2 3.2 0 0 0 1.7-.65a4.2 4.2 0 0 1 2.13-.8a.54.54 0 0 1 .23 1.05Z");
}

.oqiqno76k {
  fill: var(--svg-color--7abddc, #7abddc);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

</style>
