<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":136};
const content = `<path class="oc762obcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ifttt" /></template>
<style>
.oc762obcd {
  d: path("M0 0h43.18v135.71H0zm246.747 0h-74.024v43.18h30.843v92.53h43.181V43.18h30.843V0zm117.205 0h-74.024v43.18h30.843v92.53h43.18V43.18h30.844V0zm117.205 0h-74.024v43.18h30.843v92.53h43.18V43.18H512V0zM160.386 43.18V0h-98.7v135.71h43.181V98.7h37.013V55.52h-37.013V43.18z");
}

</style>
