<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yqlos6blb"/><rect class="jy6eswbyg"/><path class="y9kq0bbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circular-saw-site" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy6eswbyg {
  width: 18.5px;
  height: 2.5px;
  x: 2.75px;
  y: 13px;
  rx: 1px;
}

.y9kq0bbxl {
  d: path("m5 15.5l-1.25 5.75M19 15.5l1.25 5.75M4.4 18.5h15.2");
}

.yqlos6blb {
  d: path("m17.54 12.78l-.75-.79q-.2-.22-.13-.51l.25-1.06q.07-.29-.22-.38l-1.04-.31q-.29-.09-.38-.38l-.31-1.04q-.08-.29-.38-.22l-1.06.25q-.29.07-.51-.13l-.79-.75q-.22-.21-.44 0l-.79.75q-.22.2-.51.13l-1.06-.25q-.29-.07-.38.22l-.31 1.04q-.09.29-.38.38l-1.04.31q-.29.09-.22.38l.25 1.06q.07.29-.13.51l-.75.79q-.21.22.09.22h10.9q.3 0 .09-.22");
}

</style>
