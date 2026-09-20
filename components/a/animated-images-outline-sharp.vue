<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clphz0b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:animated-images-outline-sharp" /></template>
<style>
.clphz0b7d {
  fill: currentColor;
  d: path("m12 13.5l6-4l-6-4zm.825 5.5h5.425l.175 1.325l-14.725 1.8L1.85 7.2L5 6.85v2l-.9.125L5.45 19.9zM7 17V2h15v15zm2-2h11V4H9zm5.5-5.5");
}

</style>
