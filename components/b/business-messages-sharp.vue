<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxur3nbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:business-messages-sharp" /></template>
<style>
.fxur3nbry {
  fill: currentColor;
  d: path("M5.23 19V8.846L2 5h19v14zm7.366-2.5l.708-.708l-1.754-1.6h5.316v-1h-7.75zm-3.48-5.692h7.75L13.404 7.5l-.708.708l1.754 1.6H9.116z");
}

</style>
