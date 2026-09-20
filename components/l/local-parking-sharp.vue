<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y91vpvb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-parking-sharp" /></template>
<style>
.y91vpvb5c {
  fill: currentColor;
  d: path("M6 21V3h7q2.5 0 4.25 1.75T19 9t-1.75 4.25T13 15h-3v6zm4-10h3.2q.825 0 1.413-.587T15.2 9t-.587-1.412T13.2 7H10z");
}

</style>
