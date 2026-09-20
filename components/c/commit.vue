<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p109qv_yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:commit" /></template>
<style>
.p109qv_yq {
  fill: currentColor;
  d: path("M8.813 15.863Q7.45 14.725 7.1 13H2v-2h5.1q.35-1.725 1.713-2.863T12 7t3.188 1.138T16.9 11H22v2h-5.1q-.35 1.725-1.712 2.863T12 17t-3.187-1.137M12 15q1.25 0 2.125-.875T15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15");
}

</style>
