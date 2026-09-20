<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gucjt8iko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:factory-outline" /></template>
<style>
.gucjt8iko {
  fill: currentColor;
  d: path("M3 21V10.648l5-2.129v1.962l5-2V11h8v10zm1-1h16v-8h-8V9.95l-5 2V10l-3 1.325zm7.23-2.461h1.54V14.46h-1.54zm-4 0h1.54V14.46H7.23zm8 0h1.54V14.46h-1.54zM21 11h-3.116l1-7.23h1.231zM4 20h16z");
}

</style>
