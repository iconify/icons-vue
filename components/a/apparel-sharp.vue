<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wat4_7b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apparel-sharp" /></template>
<style>
.wat4_7b-a {
  fill: currentColor;
  d: path("m7 9.277l-2.452 1.352l-1.975-3.45L7.981 4h1.827v.808q0 .883.655 1.537T12 7t1.538-.655t.654-1.537V4h1.827l5.408 3.179l-1.97 3.438L17 9.283V20H7z");
}

</style>
