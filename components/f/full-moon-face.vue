<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hbslq7bfz"/><g class="dt4yhf73z"><circle class="xii8hmbyr"/><circle class="r5fl0lb3y"/><circle class="bkx_pysua"/><circle class="l-elexbss"/><circle class="ho4lh1bfe"/><circle class="u48ttbm5f"/><circle class="g5q-qcc2j"/><circle class="aqfznfb6t"/></g><path class="tx8rp-s9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:full-moon-face" /></template>
<style>
.aqfznfb6t {
  cx: 6px;
  cy: 26px;
  r: 2px;
}

.bkx_pysua {
  cx: 22px;
  cy: 5px;
  r: 2px;
}

.dt4yhf73z {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.g5q-qcc2j {
  cx: 32px;
  cy: 19px;
  r: 2px;
}

.hbslq7bfz {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18S8.059 0 18 0s18 8.059 18 18");
}

.ho4lh1bfe {
  cx: 30px;
  cy: 9px;
  r: 1px;
}

.l-elexbss {
  cx: 3px;
  cy: 18px;
  r: 1px;
}

.r5fl0lb3y {
  cx: 24.5px;
  cy: 28.5px;
  r: 3.5px;
}

.tx8rp-s9g {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M18 24.904c-7 0-9-2.618-9-1.381C9 24.762 13 28 18 28s9-3.238 9-4.477c0-1.237-2 1.381-9 1.381M27 15a3 3 0 1 1-6 0a3 3 0 0 1 6 0m-12 0a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.u48ttbm5f {
  cx: 16px;
  cy: 31px;
  r: 1px;
}

.xii8hmbyr {
  cx: 9.5px;
  cy: 7.5px;
  r: 3.5px;
}

</style>
