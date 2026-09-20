<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="yc03psz8h"/><ellipse class="ki_opobqm"/><path class="ny_cz1bhw"/><path class="gc88f_biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:crying-face" /></template>
<style>
.gc88f_biy {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M16 31c0 2.762-2.238 5-5 5s-5-2.238-5-5s4-10 5-10s5 7.238 5 10");
}

.ki_opobqm {
  cx: 24.5px;
  cy: 17px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.ny_cz1bhw {
  fill: var(--svg-color--664500, #664500);
  d: path("M5.999 13.5a1 1 0 0 1-.799-1.6c3.262-4.35 7.616-4.4 7.8-4.4a1 1 0 0 1 .004 2c-.155.002-3.568.086-6.204 3.6a1 1 0 0 1-.801.4m24.002 0a1 1 0 0 1-.801-.4c-2.641-3.521-6.061-3.599-6.206-3.6a1 1 0 0 1-.991-1.005A.997.997 0 0 1 23 7.5c.184 0 4.537.05 7.8 4.4a1 1 0 0 1-.799 1.6m-6.516 14.879C23.474 28.335 22.34 24 18 24s-5.474 4.335-5.485 4.379a.5.5 0 0 0 .232.544a.51.51 0 0 0 .596-.06C13.352 28.855 14.356 28 18 28c3.59 0 4.617.83 4.656.863a.5.5 0 0 0 .829-.484");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.yc03psz8h {
  cx: 11.5px;
  cy: 17px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

</style>
