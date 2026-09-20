<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bchtavbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-off-20-filled" /></template>
<style>
.bchtavbqg {
  fill: currentColor;
  d: path("M2.146 2.27a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-6.784-6.784a1.2 1.2 0 0 1-.363.057a1.25 1.25 0 0 1-1.195-1.615l-1.66-1.66a3.5 3.5 0 0 0 .38 4.5a.75.75 0 0 1-1.061 1.06a5 5 0 0 1-.39-6.632L5.007 5.838a6.5 6.5 0 0 0 .395 8.758a.75.75 0 0 1-1.06 1.06a8 8 0 0 1-.399-10.882L2.146 2.977a.5.5 0 0 1 0-.707m12.45 2.073a.75.75 0 0 1 1.06 0a8 8 0 0 1 .91 10.224l-1.082-1.08a6.5 6.5 0 0 0-.888-8.084a.75.75 0 0 1 0-1.06m-2.122 2.12a.75.75 0 0 1 1.06 0a5 5 0 0 1 .855 5.928l-1.127-1.127a3.5 3.5 0 0 0-.788-3.74a.75.75 0 0 1 0-1.06");
}

</style>
