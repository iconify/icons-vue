<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="p2ywf7bii"/><path class="elf7ro1xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:file-folder" /></template>
<style>
.elf7ro1xo {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M30 10h-6.562C18 10 18.562 15 15 15H6a4 4 0 0 0-4 4v10a1 1 0 1 1-2 0a4 4 0 0 0 4 4h26a4 4 0 0 0 4-4V14a4 4 0 0 0-4-4");
}

.p2ywf7bii {
  fill: var(--svg-color--269, #269);
  d: path("M0 29a4 4 0 0 0 4 4h24a4 4 0 0 0 4-4V12a4 4 0 0 0-4-4h-9c-3.562 0-3-5-8.438-5H4a4 4 0 0 0-4 4z");
}

</style>
