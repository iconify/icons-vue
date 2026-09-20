<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw0mu0z7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-open-circle" /></template>
<style>
.rw0mu0z7f {
  fill: currentColor;
  d: path("M9.5 16h5q.625 0 1.063-.437T16 14.5v-3q0-.625-.437-1.062T14.5 10V8.5q0-1.05-.725-1.775T12 6t-1.775.725T9.5 8.5H11q0-.425.288-.712T12 7.5t.713.288T13 8.5V10H9.5q-.625 0-1.062.438T8 11.5v3q0 .625.438 1.063T9.5 16m2.5 6q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
