<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yratxd2rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flight-class-outline-sharp" /></template>
<style>
.yratxd2rz {
  fill: currentColor;
  d: path("M12.616 12V5H17v7zm1-1H16V6h-2.384zM17 17H8.616L6 8.058V5h1v3l2.385 8H17zm-8.596 3v-1h8.577v1zm5.212-14H16z");
}

</style>
