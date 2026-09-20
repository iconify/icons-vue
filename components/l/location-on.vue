<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfyxi-4ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:location-on" /></template>
<style>
.tfyxi-4ek {
  fill: currentColor;
  d: path("M13.413 11.413Q14 10.825 14 10t-.587-1.412T12 8t-1.412.588T10 10t.588 1.413T12 12t1.413-.587M12 22q-4.025-3.425-6.012-6.362T4 10.2q0-3.75 2.413-5.975T12 2t5.588 2.225T20 10.2q0 2.5-1.987 5.438T12 22");
}

</style>
