<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvjmc2_ij"/><path class="i4kxf93ya"/><path class="f7d7h4keg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eat-this-much" /></template>
<style>
.bvjmc2_ij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.918 23.357c-5.291-5.291-4.107-9.58-4.107-9.58m-6.523 18.51c-2.93-2.93-2.076-7.386-2.076-7.386");
}

.f7d7h4keg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.02 19.562c1.29-1.901 4.483-2.072 7.669-1.343c.695.159 1.108-.737.552-1.184c-2.597-2.087-4.7-2.922-4.7-2.922c.58-1.626 1.88-4.067 3.411-6.32c.335-.494-.25-1.08-.744-.745c-2.254 1.53-4.695 2.83-6.32 3.411c0 0-.836-2.103-2.923-4.7c-.447-.556-1.343-.143-1.184.552c.729 3.187.558 6.379-1.343 7.67M19.3 29.865c4.146 3.225 8.476 3.718 8.476 3.718");
}

.i4kxf93ya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.421 41.579c4 4 20.253-5.827 28.474-14.048c3.3-3.3-1.628-9.303-3.375-11.05s-7.75-6.676-11.05-3.376c-8.222 8.22-18.05 24.473-14.05 28.474");
}

</style>
