<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pux2chz7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fork-chart-outline-sharp" /></template>
<style>
.pux2chz7e {
  fill: currentColor;
  d: path("M3.692 19v-7.404q-.573-.098-.94-.542t-.367-1.023V6h.769v3.23h.588V6h.785v3.23h.589V6h.769v4.03q0 .58-.368 1.024t-.94.542V19zm10.893 0q-2.935 0-4.981-2.037t-2.046-4.971q0-2.913 2.046-4.953Q11.65 5 14.585 5q2.913 0 4.953 2.04q2.039 2.039 2.039 4.952q0 2.934-2.04 4.971T14.586 19M19.15 8.14L15.266 12l3.859 3.879q.679-.783 1.066-1.776q.386-.993.386-2.113q0-1.119-.373-2.088T19.15 8.14m-4.073-2.124v4.775l3.36-3.384q-.685-.592-1.54-.958t-1.82-.433M14.577 18q1.104 0 2.088-.365q.983-.364 1.766-1.043l-4.354-4.371V6.017q-2.323.177-3.921 1.89t-1.598 4.074q0 2.508 1.755 4.264Q12.07 18 14.577 18");
}

</style>
