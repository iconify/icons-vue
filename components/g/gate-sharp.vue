<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jty3bjblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gate-sharp" /></template>
<style>
.jty3bjblr {
  fill: currentColor;
  d: path("M5 19V9q0-1.65 1.175-2.825T9 5h2v6H9v2h2v6zm8 0v-6h2v-2h-2V5h2q1.65 0 2.825 1.175T19 9v10zM2 17V7h2v10zm18 0V7h2v10z");
}

</style>
