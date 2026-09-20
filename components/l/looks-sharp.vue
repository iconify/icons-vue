<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq4an4b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-sharp" /></template>
<style>
.uq4an4b2t {
  fill: currentColor;
  d: path("M2 17q0-2.064.786-3.89q.785-1.827 2.141-3.183T8.11 7.786T12 7t3.89.786q1.827.785 3.183 2.141t2.142 3.183T22 17h-1q0-3.725-2.637-6.363T12 8t-6.362 2.638T3 17zm4 0q0-2.496 1.752-4.248T12 11t4.248 1.752T18 17h-1q0-2.075-1.463-3.537T12 12t-3.537 1.463T7 17z");
}

</style>
