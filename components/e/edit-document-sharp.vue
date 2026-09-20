<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcxtzibyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-document-sharp" /></template>
<style>
.lcxtzibyk {
  fill: currentColor;
  d: path("M4 22V2h10l6 6v2.1l-8 7.975V22zm10 0v-3.075l6.575-6.55l3.075 3.05L17.075 22zm6.575-5.6l.925-.975l-.925-.925l-.95.95zM13 9h5l-5-5l5 5l-5-5z");
}

</style>
