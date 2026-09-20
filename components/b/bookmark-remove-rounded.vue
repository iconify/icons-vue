<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucof23rfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-remove-rounded" /></template>
<style>
.ucof23rfz {
  fill: currentColor;
  d: path("M15.5 7q-.213 0-.356-.144T15 6.499t.144-.356T15.5 6h4q.213 0 .356.144t.144.357t-.144.356T19.5 7zM12 16.923l-3.738 1.608q-.808.348-1.535-.13Q6 17.926 6 17.053V5.616q0-.667.475-1.141T7.615 4h5.068q.363 0 .545.314q.182.313.04.661q-.145.365-.206.73Q13 6.07 13 6.5q0 1.742 1.157 3.012T17 10.958q.07.011.124.014q.055.003.107.003q.31.02.54.234q.229.214.229.518v5.325q0 .873-.727 1.35t-1.535.129z");
}

</style>
