<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq3-j_bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:columns-3-fill" /></template>
<style>
.nq3-j_bfe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6C2 3.7909 3.7909 2 6 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6ZM8 4L8 20L10 20L10 4L8 4ZM14 4L14 20L16 20L16 4L14 4Z");
}

</style>
