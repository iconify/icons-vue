<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4bld7bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:king-bed-outline-sharp" /></template>
<style>
.k4bld7bti {
  fill: currentColor;
  d: path("M5 19H4l-.65-2H2v-7h2V5h16v5h2v7h-1.35L20 19h-1l-.65-2H5.65zm8-9h5V7h-5zm-7 0h5V7H6zm-2 5h16v-3H4zm16 0H4z");
}

</style>
