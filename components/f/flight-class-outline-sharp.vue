<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgc6n_jgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flight-class-outline-sharp" /></template>
<style>
.wgc6n_jgl {
  fill: currentColor;
  d: path("M12 13V4h6v9zm2-2h2V6h-2zm4 7H8L5 8V4h2v4l2.5 8H18zM8 21v-2h10v2zm6-15h2z");
}

</style>
