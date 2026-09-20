<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3x8u_b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-upward-outline-sharp" /></template>
<style>
.u3x8u_b-n {
  fill: currentColor;
  d: path("M11.5 19V6.921l-5.792 5.793L5 12l7-7l7 7l-.708.714L12.5 6.92V19z");
}

</style>
