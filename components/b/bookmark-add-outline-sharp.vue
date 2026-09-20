<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q22narkzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-add-outline-sharp" /></template>
<style>
.q22narkzs {
  fill: currentColor;
  d: path("m12 18l-7 3V3h8v2H7v12.95l5-2.15l5 2.15V11h2v10zM7 5h6zm10 4V7h-2V5h2V3h2v2h2v2h-2v2z");
}

</style>
