<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pb612n0eq"/><path class="rzhpwyl5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cargr" /></template>
<style>
.pb612n0eq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 11.125c-7.131.613-11.475 1.481-16.38 2.953C10.406 19.092 4.5 24.654 4.5 30.513c0 5.906 6.519 7.633 11.811 5.46m20.112-6.944c.558-2.627 3.14-4.756 5.766-4.756h0m-4.755 0l-2.679 12.602");
}

.rzhpwyl5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.916 32.12c-.558 2.626-3.14 4.755-5.766 4.755h0c-2.627 0-4.303-2.129-3.745-4.755l.657-3.091c.558-2.627 3.14-4.756 5.766-4.756h0c2.627 0 4.303 2.13 3.745 4.756m-1.668 7.846l2.679-12.602");
}

</style>
