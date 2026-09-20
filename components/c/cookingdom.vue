<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="c6l71vbyt"/><path class="itw-g0o0e"/><path class="jeegecs-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cookingdom" /></template>
<style>
.c6l71vbyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.944 23.762s5.832 2.635 13.233 2.243s7.402-8.804 7.234-10.767s-2.187-4.598-8.523-9.084c-.526 2.958-7.423 7.227-13.9 2.832v-2.65c4.626 1.557 8.6-.084 8.6-.084c3.323.547 5.005-.946 5.005-.946c2.23-.105 1.987-2.317 1.987-2.317M5.684 12.735c-.623 2.819.617 8.118.617 8.118c-1.493.946-.168 3.343-.168 3.343c-2.103 4.374-1.761 8.591-1.761 8.591m40.964-6.121c-4.086-.682-20.698 2.64-22.97 9.874s6.57 8.39 6.57 8.39");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.itw-g0o0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.87 45.47c-.11-.94.436-1.458.436-1.458c-1.178-.982-.703-2.144-.59-2.579m-11.711-15.8c6.35 1.893 11.145 6.267 9.504 8.832s-8.873 4.668-12.995-3.785M37.7 24.49c-1.07-.44-2.48-.83-4.3-1.04");
}

.jeegecs-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.833 36.202c-.65 1.501 3.902 8.04 3.902 8.04m3.955-11.744c5.707-3.122 20.663-9.885 22.698-10.103s1.948 1.051 1.948 1.051m-25.892-9.168c-1.85-.392-2.636-.463-2.692-.477m14.061 3.267a45 45 0 0 0 2.257 1.191c-.154 3.645-.685 6.231-.685 6.231m2.101-7.534c-.575.448-1.416 1.303-1.416 1.303M11.481 9.266c-.7-1.065-1.39-1.661-1.39-1.661m4.348 10.654l1.066-1.303m1.177 1.745l.954-1.234");
}

</style>
