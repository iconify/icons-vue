<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvn4_1qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-align-vertical-bottom" /></template>
<style>
.ajvn4_1qw {
  fill: currentColor;
  d: path("M22 22H2v-2h20zM10 2H7v16h3zm7 6h-3v10h3z");
}

</style>
