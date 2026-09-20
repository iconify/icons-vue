<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqwc5httt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:discover-tune-outline-sharp" /></template>
<style>
.vqwc5httt {
  fill: currentColor;
  d: path("M13 9V7h3V3h2v4h3v2zm3 12V11h2v10zM6 21v-4H3v-2h8v2H8v4zm0-8V3h2v10z");
}

</style>
