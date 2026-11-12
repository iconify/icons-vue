<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="l4sq9d0tz"/><path class="xr94vgbux"/><path class="m86y5nxtn"/><path class="f-ijm0bse"/></g><path class="yyarl5mho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-minus-bold-duotone" /></template>
<style>
.f-ijm0bse {
  d: path("M21 5.25C21.4142 5.25 21.75 5.58579 21.75 6C21.75 6.41421 21.4142 6.75 21 6.75H3C2.58579 6.75 2.25 6.41421 2.25 6C2.25 5.58579 2.58579 5.25 3 5.25H21Z");
}

.l4sq9d0tz {
  d: path("M11 17.25C11.4142 17.25 11.75 17.5858 11.75 18C11.75 18.4142 11.4142 18.75 11 18.75H3C2.58579 18.75 2.25 18.4142 2.25 18C2.25 17.5858 2.58579 17.25 3 17.25H11Z");
}

.m86y5nxtn {
  d: path("M21 9.25C21.4142 9.25 21.75 9.58579 21.75 10C21.75 10.4142 21.4142 10.75 21 10.75H3C2.58579 10.75 2.25 10.4142 2.25 10C2.25 9.58579 2.58579 9.25 3 9.25H21Z");
}

.xr94vgbux {
  d: path("M11 13.25C11.4142 13.25 11.75 13.5858 11.75 14C11.75 14.4142 11.4142 14.75 11 14.75H3C2.58579 14.75 2.25 14.4142 2.25 14C2.25 13.5858 2.58579 13.25 3 13.25H11Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yyarl5mho {
  fill: currentColor;
  d: path("M21 15.75C21.4142 15.75 21.75 16.0858 21.75 16.5C21.75 16.9142 21.4142 17.25 21 17.25H14C13.5858 17.25 13.25 16.9142 13.25 16.5C13.25 16.0858 13.5858 15.75 14 15.75H21Z");
}

</style>
