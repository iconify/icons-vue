<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGuIWrwd1B)" class="s6z14qxqp"/><path fill="url(#SVGvJ8qPe9w)" class="v8s92ybmh"/><defs><linearGradient id="SVGuIWrwd1B" x1="3.281" x2="20.719" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop offset=".01" class="ab4w_fuel"/><stop offset="1" class="eoglvgb5t"/></linearGradient><linearGradient id="SVGvJ8qPe9w" x1="3.281" x2="19.481" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop offset=".01" class="ab4w_fuel"/><stop offset="1" class="eoglvgb5t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cast" /></template>
<style>
.ab4w_fuel {
  stop-color: var(--svg-color--cbbba0, #cbbba0);
}

.eoglvgb5t {
  stop-color: var(--svg-color--7a6037, #7a6037);
}

.ft5dv1b6b {
  fill: none;
}

.s6z14qxqp {
  d: path("M13.969 12a3.376 3.376 0 1 0 6.75 0a3.376 3.376 0 0 0-6.75 0");
}

.v8s92ybmh {
  d: path("M19.481 6.443A9.3 9.3 0 0 0 12.35 3a9.04 9.04 0 0 0-9.068 9c0 4.973 4.067 9 9.068 9c2.807 0 5.332-1.322 7.132-3.442l-2.087-2.07a6.18 6.18 0 0 1-10.099.195A6.18 6.18 0 0 1 6.094 12a6.188 6.188 0 0 1 11.3-3.487z");
}

</style>
