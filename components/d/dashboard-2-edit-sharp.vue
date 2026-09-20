<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0wnnv3-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-edit-sharp" /></template>
<style>
.v0wnnv3-z {
  fill: currentColor;
  d: path("M11.192 10.808V5H21v5.808zM3 19v-5.808h8.808V19zm0-8.192V5h5.808v5.808zM14.23 21v-2.21l5.96-5.934l2.19 2.204L16.44 21zm5.96-4.985l.925-.956l-.924-.943l-.95.95z");
}

</style>
