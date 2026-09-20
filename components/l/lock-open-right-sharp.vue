<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbscz7hex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-open-right-sharp" /></template>
<style>
.bbscz7hex {
  fill: currentColor;
  d: path("M13.413 16.413Q14 15.825 14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17t1.413-.587M4 22V8h9V6q0-2.075 1.463-3.537T18 1t3.538 1.463T23 6h-2q0-1.25-.875-2.125T18 3t-2.125.875T15 6v2h5v14z");
}

</style>
