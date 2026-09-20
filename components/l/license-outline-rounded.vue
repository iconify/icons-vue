<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otgozmbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:license-outline-rounded" /></template>
<style>
.otgozmbvq {
  fill: currentColor;
  d: path("M10.577 11.423Q10 10.846 10 10t.577-1.423T12 8t1.423.577T14 10t-.577 1.423T12 12t-1.423-.577M12 19.962l-3.963 1.184q-.385.137-.711-.115T7 20.375v-5.504q-.95-.934-1.475-2.188T5 10q0-2.927 2.036-4.963T12 3t4.964 2.036T19 10q0 1.429-.525 2.683T17 14.87v5.504q0 .404-.326.656t-.71.115zm4.25-5.712Q18 12.5 18 10t-1.75-4.25T12 4T7.75 5.75T6 10t1.75 4.25T12 16t4.25-1.75M8 20.044l4-1.121l4 1.121v-4.33q-.836.615-1.859.95Q13.12 17 12 17t-2.141-.335T8 15.714zm4-2.165");
}

</style>
