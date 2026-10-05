<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7ikox8ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-simple-sharp-fill" /></template>
<style>
.v7ikox8ri {
  fill: currentColor;
  d: path("M11.3857 2.2071C11.7469 1.92603 12.2531 1.92603 12.6143 2.2071L21.6143 9.21101C21.8575 9.40048 22 9.6917 22 10.0001V21.0001C21.9998 21.5522 21.5522 22.0001 21 22.0001H3C2.44783 22.0001 2.00018 21.5522 2 21.0001V10.0001C2 9.6917 2.14246 9.40048 2.38574 9.21101L11.3857 2.2071Z");
}

</style>
