<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3tgw0b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-north-west" /></template>
<style>
.v3tgw0b9a {
  fill: currentColor;
  d: path("M5 15h2V8.41L18.59 20L20 18.59L8.41 7H15V5H5z");
}

</style>
