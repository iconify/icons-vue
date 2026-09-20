<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3x6us0lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:inbox-sharp" /></template>
<style>
.v3x6us0lg {
  fill: currentColor;
  d: path("M3 21V3h18v18zm10.725-5.55Q14.5 14.9 14.8 14H19V5H5v9h4.2q.3.9 1.075 1.45T12 16t1.725-.55");
}

</style>
