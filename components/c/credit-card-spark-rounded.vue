<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt2l_pbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-spark-rounded" /></template>
<style>
.zt2l_pbjy {
  fill: currentColor;
  d: path("M18.404 21q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.89q0 .213-.143.357t-.357.143t-.357-.143t-.143-.357V8.808H4v2.384h9.34q.46 0 .627.445t-.2.784q-1.13 1.181-1.584 2.724t-.098 3.147q.061.274-.098.49t-.431.218z");
}

</style>
