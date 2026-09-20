<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="agwt7zb7l"/><path class="pf3cr9quj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:flower-bud" /></template>
<style>
.agwt7zb7l {
  fill-rule: evenodd;
  d: path("M16.49 13.714a4.003 4.003 0 0 0 0-7.427q.01-.143.01-.287A4 4 0 0 0 10 2.877a4 4 0 0 0-6.49 3.41a4.003 4.003 0 0 0 0 7.427q-.01.142-.01.286a4 4 0 0 0 6.5 3.123a4 4 0 0 0 6.49-3.41m-2.108-7.036a1 1 0 0 0 .835 1.334a2 2 0 0 1 0 3.976a1 1 0 0 0-.835 1.334q.117.324.118.678a2 2 0 0 1-3.667 1.105a1 1 0 0 0-1.666 0a2 2 0 0 1-3.55-1.783a1 1 0 0 0-.834-1.333a2 2 0 0 1 0-3.977a1 1 0 0 0 .835-1.334a2 2 0 0 1 3.55-1.783a1 1 0 0 0 1.665 0a2 2 0 0 1 3.55 1.783");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pf3cr9quj {
  d: path("M13.5 10a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0");
}

</style>
