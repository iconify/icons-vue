<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8ipwxb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apparel-outline-sharp" /></template>
<style>
.t8ipwxb3g {
  fill: currentColor;
  d: path("m7 9.277l-2.452 1.352l-1.975-3.45L7.981 4h1.827v.808q0 .883.655 1.537T12 7t1.538-.655t.654-1.537V4h1.827l5.408 3.179l-1.97 3.438L17 9.283V20H7zM8 7.6V19h8V7.6l3.062 1.68l1.011-1.73l-4.28-2.538h-.635q-.087 1.255-.98 2.122Q13.285 8 12 8t-2.178-.866t-.98-2.123h-.634L3.927 7.55l1.012 1.73zm4 4.406");
}

</style>
