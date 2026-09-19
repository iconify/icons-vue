<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yk37xvbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blixt-wallet" /></template>
<style>
.yk37xvbtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.565 20.918l-21.584 3.597L27.408 3.5l-7.725 17.392zm-17.13 6.164l21.584-3.597L20.592 44.5l7.725-17.392z");
}

</style>
