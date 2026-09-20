<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ofpwbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:factory" /></template>
<style>
.n9ofpwbpl {
  fill: currentColor;
  d: path("M3 21V10.648l5-2.129v1.962l5-2.02V11h8v10zm8.23-3.462h1.54v-3.076h-1.54zm-4 0h1.54v-3.076H7.23zm8 0h1.54v-3.076h-1.54zm5.647-7.423h-2.875l.889-6.346h1.225z");
}

</style>
