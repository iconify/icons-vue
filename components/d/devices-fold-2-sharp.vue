<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltiy7bbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-fold-2-sharp" /></template>
<style>
.ltiy7bbyl {
  fill: currentColor;
  d: path("M6.02 20V4h12.276l3.404 8.5h-3.488V20zm1-1h10.192v-6.5H8.935L7.018 7.721z");
}

</style>
