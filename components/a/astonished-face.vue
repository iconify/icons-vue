<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="wt7dtpb1h"/><path class="cxdjcot4w"/><path class="qobzl5muc"/><ellipse class="glt062toh"/><ellipse class="ac5w7ac7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:astonished-face" /></template>
<style>
.ac5w7ac7u {
  cx: 24px;
  cy: 14.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.cxdjcot4w {
  fill: var(--svg-color--664500, #664500);
  d: path("M5.999 11A1 1 0 0 1 5.2 9.4C8.462 5.05 12.816 5 13 5a1 1 0 0 1 .004 2c-.155.002-3.568.086-6.204 3.6a1 1 0 0 1-.801.4m24.002 0a1 1 0 0 1-.801-.4c-2.64-3.521-6.061-3.598-6.206-3.6a1 1 0 0 1-.991-1.005A.997.997 0 0 1 23 5c.184 0 4.537.05 7.8 4.4a1 1 0 0 1-.799 1.6");
}

.glt062toh {
  cx: 12px;
  cy: 14.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.qobzl5muc {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M18 23c-1.657 0-3 1.79-3 4h6c0-2.21-1.343-4-3-4");
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
