<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf78gt-nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gamepad-sharp" /></template>
<style>
.hf78gt-nw {
  fill: currentColor;
  d: path("m12 10.5l-3-3V2h6v5.5zm4.5 4.5l-3-3l3-3H22v6zM2 15V9h5.5l3 3l-3 3zm7 7v-5.5l3-3l3 3V22z");
}

</style>
