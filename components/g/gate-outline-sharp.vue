<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jafur8bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gate-outline-sharp" /></template>
<style>
.jafur8bvs {
  fill: currentColor;
  d: path("M2 17V7h2v10zm3 2V9q0-1.65 1.175-2.825T9 5h6q1.65 0 2.825 1.175T19 9v10zm15-2V7h2v10zM7 17h4v-4H9v-2h2V7H9q-.825 0-1.412.588T7 9zm6 0h4V9q0-.825-.587-1.412T15 7h-2v4h2v2h-2z");
}

</style>
