<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fl2-opbfh"/><path class="ncpq23orh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-destroyed" /></template>
<style>
.fl2-opbfh {
  d: path("M7.899 20.856C5.568 20.371 4 19.49 4 18.5v-13c0-1.346 2.898-2.491 6.672-2.712m5.834.446C18.612 3.734 20 4.569 20 5.5v13c0 1.287-2.652 2.391-6.185 2.678");
}

.ncpq23orh {
  d: path("M4 5.5c0 1.109 1.969 2.082 4.775 2.513m5.896.077C17.768 7.707 20 6.681 20 5.5M4 12c0 1.32 2.786 2.446 6.452 2.698m6.143-.454C18.651 13.743 20 12.918 20 12M14 2l-3 8l2.5 4.5l-3 7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
