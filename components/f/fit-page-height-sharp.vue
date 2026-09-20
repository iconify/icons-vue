<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv562z2_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-page-height-sharp" /></template>
<style>
.qv562z2_f {
  fill: currentColor;
  d: path("M9 9h6l-3-3zm3 9l3-3H9zm8 4H4V2h16z");
}

</style>
