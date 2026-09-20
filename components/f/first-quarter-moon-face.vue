<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ftx0lnbus"/><g class="dt4yhf73z"><circle class="z763orbsc"/><circle class="nq8tz9lfr"/><circle class="sfc_ew8rt"/><circle class="yi1dqlbex"/></g><path class="oo5_9ybop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:first-quarter-moon-face" /></template>
<style>
.dt4yhf73z {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.ftx0lnbus {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M25 13c0-4.984-1.934-9.505-5.073-12.894C28.961 1.068 36 8.71 36 18c0 9.941-8.06 18-18 18c-4.303 0-8.25-1.515-11.347-4.033c7.163-.245 13.305-4.451 16.35-10.484c.622-1.232-2.795-1.201-2.962-3.482C19.887 15.87 25 15.26 25 13");
}

.nq8tz9lfr {
  cx: 27px;
  cy: 7px;
  r: 1px;
}

.oo5_9ybop {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M19.797 26.023a19.4 19.4 0 0 0 2.104-2.651c5.449 1.226 7.637-.273 7.316.807c-.34 1.147-4.797 3.008-9.42 1.844M26 14.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0");
}

.sfc_ew8rt {
  cx: 18px;
  cy: 32px;
  r: 1px;
}

.yi1dqlbex {
  cx: 33px;
  cy: 20px;
  r: 2px;
}

.z763orbsc {
  cx: 25.5px;
  cy: 28.5px;
  r: 3.5px;
}

</style>
