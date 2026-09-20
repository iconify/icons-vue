<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o5sud5bxx"/><path class="v0yxn1uoq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dps" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o5sud5bxx {
  fill: var(--svg-color--d400a6, #d400a6);
  d: path("M3 14.47c0-.841.937-2.304 1.403-2.927c-.148.328-.448.946-.448 1.546c0 2.603 4.593 2.35 6.891 1.892c-.77.393-2.788 1.177-4.675 1.177C3.817 16.158 3 15.521 3 14.47m18-4.93c0 .84-.992 2.303-1.486 2.926c.157-.328.475-.946.475-1.546c0-2.603-4.864-2.35-7.297-1.892c.817-.393 2.954-1.177 4.953-1.177C20.137 7.85 21 8.488 21 9.54");
}

.v0yxn1uoq {
  fill: var(--svg-color--7f16d3, #7f16d3);
  d: path("M18.715 12.005a6.927 6.927 0 0 1-11.981 4.744l.032.01c1.07.083 5.29-.485 7.615-3.919c-.923.512-3.304 1.537-5.413 1.537c-1.884 0-3.088-.434-3.993-1.038a6.927 6.927 0 0 1 11.871-6.065a.3.3 0 0 0-.088-.023c-1.061-.083-5.261.485-7.578 3.918c.923-.512 3.29-1.537 5.386-1.537c1.915 0 3.115.453 4.025 1.071c.083.42.124.859.124 1.302");
}

</style>
