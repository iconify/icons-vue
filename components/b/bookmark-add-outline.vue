<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fim1mbm1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-add-outline" /></template>
<style>
.fim1mbm1i {
  fill: currentColor;
  d: path("M6 19.5V5.616q0-.691.463-1.153T7.616 4H13v1H7.616q-.231 0-.424.192T7 5.616V17.95l5-2.15l5 2.15V11h1v8.5l-6-2.577zM7 5h6zm10 4V7h-2V6h2V4h1v2h2v1h-2v2z");
}

</style>
