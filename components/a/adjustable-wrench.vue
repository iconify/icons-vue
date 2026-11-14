<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3m0vzb3z"/><path class="xq347jb-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adjustable-wrench" /></template>
<style>
.n3m0vzb3z {
  d: path("m15.182 1.747l2.475 2.475l-2.829 2.828l2.122 2.122l1.768-1.768l2.121 2.121l-3.889 3.889l-3.182-.353l-2.829-2.829l-.707-3.535Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xq347jb-p {
  d: path("m10.939 10.232l2.829 2.829l-7.071 7.071l-2.829-2.829Zm4.42.531l2.121 2.121");
}

</style>
