<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3easlsll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-awesome-motion-sharp" /></template>
<style>
.o3easlsll {
  fill: currentColor;
  d: path("M10 22V10h12v12zm-4-4V6h12v2H8v10zm-4-4V2h12v2H4v10z");
}

</style>
