<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa80itulk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-open-right-outline-sharp" /></template>
<style>
.sa80itulk {
  fill: currentColor;
  d: path("M6 20h12V10H6zm7.413-3.588Q14 15.826 14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17t1.413-.587M6 20V10zm-2 2V8h9V6q0-2.075 1.463-3.537T18 1t3.538 1.463T23 6h-2q0-1.25-.875-2.125T18 3t-2.125.875T15 6v2h5v14z");
}

</style>
