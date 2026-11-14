<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pcezlfkkd"/><path class="bwldmrbus"/><path class="rx3gxnn5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adrenal-gland" /></template>
<style>
.bwldmrbus {
  fill: currentColor;
  d: path("m8.5 5l7-.25l-2.5-2.5Z");
}

.pcezlfkkd {
  d: path("M12.25 6.25C8.5 6.25 6 9.5 6 13.5s2.5 7.25 6.25 7.25c2.25 0 3.75-1.25 3.25-3.25c-.5-1.5-2.25-2.25-2.25-4S15 11 15.5 9.5c.5-2-1-3.25-3.25-3.25Z");
}

.rx3gxnn5f {
  d: path("M13.25 13.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
