<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ngpmpqbbo"/><ellipse class="tm02q9b_a"/><path class="hbnuo8b7f"/><ellipse class="glt062toh"/><ellipse class="ac5w7ac7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hushed-face" /></template>
<style>
.ac5w7ac7u {
  cx: 24px;
  cy: 14.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.glt062toh {
  cx: 12px;
  cy: 14.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.hbnuo8b7f {
  fill: var(--svg-color--664500, #664500);
  d: path("M31.001 11a1 1 0 0 1-.801-.4c-2.64-3.521-6.061-3.598-6.206-3.6a1 1 0 0 1-.991-1.005A.997.997 0 0 1 24 5c.184 0 4.537.05 7.8 4.4a1 1 0 0 1-.799 1.6M4.999 11A1 1 0 0 1 4.2 9.4C7.462 5.05 11.816 5 12 5a1 1 0 0 1 .004 2c-.155.002-3.568.086-6.204 3.6a1 1 0 0 1-.801.4");
}

.ngpmpqbbo {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18S8.059 0 18 0s18 8.059 18 18");
}

.tm02q9b_a {
  cx: 18px;
  cy: 25.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 3px;
  ry: 3.5px;
}

</style>
