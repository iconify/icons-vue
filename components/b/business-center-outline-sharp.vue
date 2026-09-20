<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkkjqhk1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:business-center-outline-sharp" /></template>
<style>
.lkkjqhk1h {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm8-15h4V4h-4zm10 9h-5v2H9v-2H4v4h16zm-9 0h2v-2h-2zm-7-2h5v-2h6v2h5V8H4zm8 1");
}

</style>
