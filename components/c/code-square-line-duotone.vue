<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b_mqzbbbw"/><path class="r6t4zeiqh"/><path class="lr4e9yb5j"/><path class="lxnzn9nmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-square-line-duotone" /></template>
<style>
.b_mqzbbbw {
  d: path("M15.5 9L15.6716 9.17157C17.0049 10.5049 17.6716 11.1716 17.6716 12C17.6716 12.8284 17.0049 13.4951 15.6716 14.8284L15.5 15");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr4e9yb5j {
  d: path("M8.4997 9L8.32813 9.17157C6.99479 10.5049 6.32812 11.1716 6.32812 12C6.32812 12.8284 6.99479 13.4951 8.32813 14.8284L8.4997 15");
}

.lxnzn9nmw {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r6t4zeiqh {
  d: path("M13.2939 7.17038L11.9998 12L10.7058 16.8296");
}

</style>
