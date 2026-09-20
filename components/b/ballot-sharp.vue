<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_ay5_b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ballot-sharp" /></template>
<style>
.b_ay5_b2r {
  fill: currentColor;
  d: path("M12 10h5V8h-5zm0 6h5v-2h-5zm-5-5h4V7H7zm0 6h4v-4H7zm-4 4V3h18v18z");
}

</style>
