<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qelau6czp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:civic-award" /></template>
<style>
.qelau6czp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.007 9.502q.755.421 1.412 1.079Q18.25 12.411 18.25 15t-1.831 4.419T12 21.25t-4.419-1.831Q5.75 17.589 5.75 15t1.831-4.419q.657-.658 1.412-1.079L6.304 2.779q-.028-.069-.041-.142t-.013-.146t.016-.146t.045-.14t.071-.129t.094-.113t.115-.092t.13-.067Q6.856 1.75 7 1.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .144-.054.279zm-4.621-.556Q11.152 8.75 12 8.75t1.614.196l2.278-5.696H8.108zM8.75 15q0-3.25 3.25-3.25T15.25 15T12 18.25T8.75 15");
}

</style>
