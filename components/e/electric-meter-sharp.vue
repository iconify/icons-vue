<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qakng2bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-meter-sharp" /></template>
<style>
.qakng2bhy {
  fill: currentColor;
  d: path("M9.5 20.68v-2.114q-2.42-.791-3.96-2.863T4 10.95q0-1.663.626-3.118T6.34 5.29t2.542-1.714t3.093-.626q1.658 0 3.116.626q1.457.626 2.548 1.714q1.09 1.087 1.726 2.542T20 10.95q0 2.662-1.543 4.728q-1.544 2.066-3.957 2.863v2.14h-1v-1.877q-.385.088-.76.117q-.374.029-.765.029q-.384 0-.747-.032t-.728-.114v1.877zM8.5 8.5h7v-1h-7zm2.75 7.789l2.192-2.193l-1.25-1.25l1.346-1.346l-.788-.788l-2.192 2.192l1.25 1.25l-1.346 1.346z");
}

</style>
