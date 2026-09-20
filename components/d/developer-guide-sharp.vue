<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shluewb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:developer-guide-sharp" /></template>
<style>
.shluewb7s {
  fill: currentColor;
  d: path("M4 20V4h16v16zm8.5-15v6.116l2-1.193l2 1.193V5z");
}

</style>
