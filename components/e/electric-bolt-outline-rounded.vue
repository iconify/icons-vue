<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdke2gb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-bolt-outline-rounded" /></template>
<style>
.tdke2gb4b {
  fill: currentColor;
  d: path("m11.712 14l-5.945-.692q-.528-.056-.677-.56t.243-.852l9.783-8.78q.067-.068.155-.101q.088-.034.254-.034q.27 0 .426.233t.003.49l-3.723 6.315l5.983.692q.528.056.687.55t-.234.843l-9.783 8.8q-.067.067-.155.091t-.254.024q-.27 0-.407-.232t-.003-.471zm-1.2 4.017l7.179-6.369l-7.072-.792l2.902-4.906l-7.212 6.389l7.047.844zM12 11.981");
}

</style>
