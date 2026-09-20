<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w07rw0m7j"/><g class="dt4yhf73z"><circle class="qqf1mybwc"/><circle class="jrwuu8bky"/><circle class="sfc_ew8rt"/><circle class="r3n5afzsk"/></g><path class="np5r_wb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:last-quarter-moon-with-face" /></template>
<style>
.dt4yhf73z {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.jrwuu8bky {
  cx: 9px;
  cy: 7px;
  r: 1px;
}

.np5r_wb0p {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M16.203 26.023a19.4 19.4 0 0 1-2.104-2.651c-5.449 1.226-7.637-.273-7.316.807c.341 1.147 4.797 3.008 9.42 1.844M10 14.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0");
}

.qqf1mybwc {
  cx: 10.5px;
  cy: 28.5px;
  r: 3.5px;
}

.r3n5afzsk {
  cx: 3px;
  cy: 20px;
  r: 2px;
}

.sfc_ew8rt {
  cx: 18px;
  cy: 32px;
  r: 1px;
}

.w07rw0m7j {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M11 13c0-4.984 1.934-9.505 5.073-12.894C7.039 1.068 0 8.71 0 18c0 9.941 8.06 18 18 18a17.93 17.93 0 0 0 11.348-4.033c-7.164-.245-13.306-4.451-16.351-10.484c-.622-1.232 2.795-1.201 2.962-3.482C16.113 15.87 11 15.26 11 13");
}

</style>
