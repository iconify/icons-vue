<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5vqt1b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gadget-cracked-screen" /></template>
<style>
.b5vqt1b8n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.125 1.75h-2.25q-2.123 0-3.624 1.501T5.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h2.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T13.125 1.75m-.785 6.635l2.27 3.179q.065.091.101.198q.036.106.039.218t-.027.22t-.09.203l-3.5 5.5q-.04.062-.091.115t-.112.096t-.128.072q-.067.03-.139.046t-.146.018q-.074.001-.147-.011t-.141-.04q-.069-.027-.132-.066q-.062-.04-.115-.091t-.096-.112t-.072-.128t-.046-.139t-.018-.146t.011-.147t.04-.141t.066-.132l3.229-5.073l-2.206-3.088q-.053-.074-.087-.159t-.046-.176t-.003-.181t.041-.176l2-5.5q.025-.07.064-.133q.038-.063.088-.118t.109-.098t.127-.075t.139-.048q.071-.018.145-.021t.147.008t.142.036q.141.051.251.152t.173.236t.069.284t-.044.289z");
}

</style>
