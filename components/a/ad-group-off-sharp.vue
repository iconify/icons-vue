<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmqhmkbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-group-off-sharp" /></template>
<style>
.zmqhmkbct {
  fill: currentColor;
  d: path("M20.423 21.839L15.585 17H6.5V7.916L2.162 3.577l.707-.708l18.262 18.262zM3.5 20V6.616h1V19h12.385v1zm16.142-3.183L8.825 6H19.5V4H7.52v.694l-.837-.836V3H20.5v13.817z");
}

</style>
