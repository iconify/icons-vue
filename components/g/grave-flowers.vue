<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re5hfnbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grave-flowers" /></template>
<style>
.re5hfnbpo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2Q9.5 2 9.5 4.5q0 2.092 1.75 2.433v7.506l-4.445-5.3q.245-.153.463-.371Q8 8.036 8 7t-.732-1.768T5.5 4.5Q3 4.5 3 7q0 2.312 2.138 2.486l5.254 6.264H5.25q-1.243 0-2.121.879q-.879.878-.879 2.121t.879 2.121q.878.879 2.121.879h13.5q3 0 3-3t-3-3h-5.142l5.263-6.275q.799-.11 1.397-.707Q21 8.036 21 7t-.732-1.768T18.5 4.5Q16 4.5 16 7q0 1.674 1.121 2.227l-4.371 5.212V6.892q.566-.173 1.018-.624q.732-.732.732-1.768t-.732-1.768T12 2");
}

</style>
