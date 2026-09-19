<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGUHaPQbup" class="nid50qnzx"/></defs><path class="p8aqisb0v"/><use href="#SVGUHaPQbup" class="c-zrgpb5l"/><use href="#SVGUHaPQbup" class="c-zrgpb5l"/><path class="v1in0cqtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-mushroom" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nid50qnzx {
  fill: none;
  stroke: currentColor;
  d: path("M42.5 24.296c0 6.541-8.283 6.662-18.5 6.662s-18.5-.12-18.5-6.662S13.783 7.271 24 7.271s18.5 10.484 18.5 17.025");
}

.p8aqisb0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.435 30.867v8.835s-.087 1.005 1.87 1.005h8.709s1.668.294 1.668-1.273v-8.536");
}

.v1in0cqtb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.192 10.549s3.472 10.453-8.085 10.372c0 0 2.224-6.71 8.085-10.372m19.546 0s-3.472 10.453 8.084 10.372c0 0-2.223-6.71-8.084-10.372M18.065 21.476c-.002 2.525 2.654 4.573 5.932 4.574s5.937-2.045 5.938-4.57v-.004c0-2.525-2.657-4.572-5.935-4.572s-5.935 2.047-5.935 4.572");
}

</style>
