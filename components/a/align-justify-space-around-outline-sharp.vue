<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob8ngzfqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-space-around-outline-sharp" /></template>
<style>
.ob8ngzfqa {
  fill: currentColor;
  d: path("M20 22V2h2v20zM2 22V2h2v20zm13-5V7h3v10zm-9 0V7h3v10z");
}

</style>
