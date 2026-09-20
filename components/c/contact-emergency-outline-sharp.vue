<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk72_izbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-emergency-outline-sharp" /></template>
<style>
.bk72_izbw {
  fill: currentColor;
  d: path("M1 19.616V4.385h22v15.23zm13.785-1H22V5.385H2v13.23h1.216q1.05-1.355 2.553-2.177T9 15.616t3.23.822t2.555 2.178M10.769 13.5q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-6.22 5.116h8.9q-.87-.95-2.022-1.475q-1.153-.525-2.428-.525t-2.425.525t-2.025 1.475m3.391-5.826q-.441-.442-.441-1.06t.441-1.058T9 10.231t1.059.441t.441 1.059t-.441 1.059q-.442.44-1.059.44t-1.059-.44m9.617-1.098h.884v-1.93l1.668.965l.442-.762L18.884 9l1.668-.965l-.442-.762l-1.668.966V6.308h-.884v1.93l-1.667-.965l-.443.762L17.116 9l-1.668.966l.443.761l1.667-.965z");
}

</style>
