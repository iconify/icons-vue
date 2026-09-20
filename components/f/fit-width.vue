<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rts2tzbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fit-width" /></template>
<style>
.rts2tzbku {
  fill: currentColor;
  d: path("M4 20V4h1.23v16zm14.77 0V4H20v16zM7.691 12.616v-1.231h1.231v1.23zm3.693 0v-1.231h1.23v1.23zm3.692 0v-1.231h1.23v1.23z");
}

</style>
