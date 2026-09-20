<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="u7cmxsrmb"/><path class="rzvljivpm"/><path class="ls_otbbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:autoit" /></template>
<style>
.ls_otbbny {
  fill: var(--svg-color--f0f0f0, #f0f0f0);
  d: path("m206.41 166l-58.52-84.7q-3.08-4.478-7.49-7.49q-4.41-3.01-10.99-3.01q-6.861 0-11.34 3.22q-4.481 3.221-7.42 7.28L50.59 166h34.3l43.96-62.16l16.8 24.78a377 377 0 0 1 4.97 7.21q2.589 3.851 4.55 6.37q-3.361-.28-7.91-.28h-32.27L97.49 166z");
}

.rzvljivpm {
  fill: var(--svg-color--f0f0f0, #f0f0f0);
  d: path("M0 128C0 57.308 57.308 0 128 0s128 57.308 128 128s-57.308 128-128 128S0 198.692 0 128M128 25.5C71.39 25.5 25.5 71.39 25.5 128S71.39 230.5 128 230.5S230.5 184.61 230.5 128S184.61 25.5 128 25.5");
}

.u7cmxsrmb {
  cx: 128px;
  cy: 128px;
  r: 114.75px;
  fill: var(--svg-color--5d83ac, #5d83ac);
}

</style>
