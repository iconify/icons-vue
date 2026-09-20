<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0bvkcbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-legroom-extra-outline-sharp" /></template>
<style>
.h0bvkcbfe {
  fill: currentColor;
  d: path("M12.77 16.5h-10v-13h1v12h9zm5.36 3.577L15.386 14.5H5.654v-11h5v7h4.821l3.571 7.292l2.527-1.067l.752 1.433z");
}

</style>
