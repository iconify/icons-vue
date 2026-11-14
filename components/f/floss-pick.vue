<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v8gh40b8o"/><path class="yq5tygk5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floss-pick" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8gh40b8o {
  d: path("m8.818 12.354l2.828 2.828l-6.01 6.01l-2.828-2.828Z");
}

.yq5tygk5i {
  d: path("M14.828 3.515L11.293 7.05l-1.061 6.718l6.718-1.061l3.535-3.535m-5.657-5.657l5.657 5.657");
}

</style>
