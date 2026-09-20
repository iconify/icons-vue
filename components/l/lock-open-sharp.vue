<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3t_q2i4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-open-sharp" /></template>
<style>
.t3t_q2i4n {
  fill: currentColor;
  d: path("M4 22V8h11V6q0-1.25-.875-2.125T12 3t-2.125.875T9 6H7q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6v2h3v14zm9.413-5.587Q14 15.825 14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17t1.413-.587");
}

</style>
