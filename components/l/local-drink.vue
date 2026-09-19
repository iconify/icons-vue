<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bep02fb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:local-drink" /></template>
<style>
.bep02fb0z {
  fill: currentColor;
  d: path("m3 2l2.01 18.23C5.13 21.23 5.97 22 7 22h10c1.03 0 1.87-.77 1.99-1.77L21 2zm9 17c-1.66 0-3-1.34-3-3c0-2 3-5.4 3-5.4s3 3.4 3 5.4c0 1.66-1.34 3-3 3m6.33-11H5.67l-.44-4h13.53z");
}

</style>
