<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="wt7dtpb1h"/><path class="mo811lbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-crossed-out-eyes" /></template>
<style>
.mo811lbzm {
  fill: var(--svg-color--664500, #664500);
  d: path("M5.999 11A1 1 0 0 1 5.2 9.4C8.462 5.05 12.816 5 13 5a1 1 0 0 1 .004 2c-.155.002-3.568.086-6.204 3.6a1 1 0 0 1-.801.4m24.002 0a1 1 0 0 1-.801-.4c-2.64-3.521-6.061-3.598-6.206-3.6a1 1 0 0 1-.991-1.005A.997.997 0 0 1 23 5c.184 0 4.537.05 7.8 4.4a1 1 0 0 1-.799 1.6m-16.087 4.5l1.793-1.793a.999.999 0 1 0-1.414-1.414L12.5 14.086l-1.793-1.793a.999.999 0 1 0-1.414 1.414l1.793 1.793l-1.793 1.793a.999.999 0 1 0 1.414 1.414l1.793-1.793l1.793 1.793a.997.997 0 0 0 1.414 0a1 1 0 0 0 0-1.414zm11 0l1.793-1.793a.999.999 0 1 0-1.414-1.414L23.5 14.086l-1.793-1.793a.999.999 0 1 0-1.414 1.414l1.793 1.793l-1.793 1.793a.999.999 0 1 0 1.414 1.414l1.793-1.793l1.793 1.793a.997.997 0 0 0 1.414 0a1 1 0 0 0 0-1.414z");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.wt7dtpb1h {
  cx: 18px;
  cy: 27px;
  fill: var(--svg-color--664500, #664500);
  rx: 5px;
  ry: 6px;
}

</style>
