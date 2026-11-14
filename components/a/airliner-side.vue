<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g84vdnbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:airliner-side" /></template>
<style>
.g84vdnbpj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 16.25q-2.25 0-2.25-3.25q0-.053.008-.106l1-7q.009-.067.03-.13q.021-.064.053-.123q.033-.059.075-.111t.093-.097q.05-.044.108-.078t.121-.058t.129-.035t.133-.012h2q.101 0 .199.027q.097.026.184.078t.157.124q.07.073.118.162l2.787 5.109H18q4.25 0 4.25 2.75q0 2.591-3.772 2.741q.022.181.022.384q0 1.875-1.875 1.875h-1.75q-1.407 0-1.758-1.056l-2.148 2.147q-.659.659-1.59.659H8.75q-.85 0-1.23-.76t.13-1.44L9 16.25z");
}

</style>
