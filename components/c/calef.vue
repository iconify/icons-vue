<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p49x_vb1l"/><path class="r-xh4mbvw"/><path class="atzy9sb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calef" /></template>
<style>
.atzy9sb-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.627 34.958h10.169v4.918H29.627zm-11.28-10.544s.032 9.855 7.078 11.31m.73-2l-1.497 4.106l3.197-1.224Z");
}

.p49x_vb1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.287 7.977h5.087m3.807 0h1.291a1.686 1.686 0 0 1 1.69 1.689v21.28a1.69 1.69 0 0 1-.833 1.458m-4.708.231H7.189a1.686 1.686 0 0 1-1.689-1.69V9.666a1.686 1.686 0 0 1 1.69-1.688h1.29");
}

.r-xh4mbvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.59 5.6h1.587a1.11 1.11 0 0 1 1.11 1.11v1.883a1.11 1.11 0 0 1-1.11 1.11H9.591a1.11 1.11 0 0 1-1.11-1.11V6.71a1.11 1.11 0 0 1 1.11-1.11m8.894 0h1.586a1.11 1.11 0 0 1 1.11 1.11v1.883a1.11 1.11 0 0 1-1.11 1.11h-1.586a1.11 1.11 0 0 1-1.11-1.11V6.71a1.11 1.11 0 0 1 1.11-1.11M16.78 27.884H7.71V12.728h14.24v15.156h-1.049M14.83 12.728v15.156m-3.924-15.156v15.156m7.85-15.156v7.578m3.194 0H7.71m14.24-3.926H7.71m7.12 7.851H7.71m19.213 7.751v-2.268H42.5v12.685H26.923v-3.076m2.637-7.086h10.303");
}

</style>
