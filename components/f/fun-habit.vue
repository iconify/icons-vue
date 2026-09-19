<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z45aunbxs"/><g class="y9tr6bcfx"><path class="k7nn9w6eh"/><path class="dv1sk9lsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fun-habit" /></template>
<style>
.dv1sk9lsn {
  d: path("M28.559 5.5h8.564c1.186 0 2.142.955 2.142 2.141v16.437l-4.29-2.437l-4.276 2.437V7.64a2.137 2.137 0 0 0-2.141-2.14");
}

.k7nn9w6eh {
  d: path("M25.982 7.725V7.64c0-1.186.955-2.14 2.142-2.14h.832");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z45aunbxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.268 9.734a8.54 8.54 0 0 1 3.043 6.556v17.645a8.546 8.546 0 0 1-8.566 8.565h-19.49a8.546 8.546 0 0 1-8.566-8.565V16.29a8.546 8.546 0 0 1 8.566-8.564H30.7M13.209 20.209h11.174M13.209 31.308h20.14");
}

</style>
