<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyybp-h2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-retrolux" /></template>
<style>
.vyybp-h2d {
  fill: currentColor;
  d: path("m15.05 21.95l-2.25-2.3q-.425 1.05-1.312 1.7T9.5 22q-1.475 0-2.488-1.012T6 18.5t1.013-2.488T9.5 15q.35 0 .7.05t.65.2L6 8l6-6l6 6l-5 7.5v1.55l3.45 3.45zm-4.487-2.387Q11 19.125 11 18.5t-.437-1.062T9.5 17t-1.062.438T8 18.5t.438 1.063T9.5 20t1.063-.437");
}

</style>
