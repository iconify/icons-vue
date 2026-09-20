<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcd5lvnvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hotel-outline" /></template>
<style>
.hcd5lvnvw {
  fill: currentColor;
  d: path("M2 18V5h1v9h8.5V7H19q1.238 0 2.119.881T22 10v8h-1v-3H3v3zm3.5-6.502q-.615-.618-.615-1.5T5.502 8.5t1.5-.615t1.498.617t.616 1.5t-.618 1.498t-1.5.616t-1.498-.618m7 2.502H21v-4q0-.825-.587-1.412T19 8h-6.5zm-4.71-3.21q.326-.326.326-.79t-.326-.79T7 8.886t-.79.326t-.325.789t.326.79t.789.326t.79-.326M12.5 8v6z");
}

</style>
