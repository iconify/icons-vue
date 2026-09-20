<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rp1d5d1tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-add-16-filled" /></template>
<style>
.rp1d5d1tr {
  fill: currentColor;
  d: path("M11.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M8.44 2a2.5 2.5 0 0 0-.383.747L5.023 12.35a.5.5 0 1 0 .954.3l.218-.695c.136.496.339.963.599 1.393a1.5 1.5 0 0 1-1.184.651a2.5 2.5 0 0 1-2.096-1.249l-2.309-4a1.5 1.5 0 0 1 0-1.5l2.598-4.5A1.5 1.5 0 0 1 5.102 2zm3.06 6a.5.5 0 0 0-.5.5V10H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 1 0 1 0V11h1.5a.5.5 0 0 0 0-1H12V8.5a.5.5 0 0 0-.5-.5m-1.112-5.999a2.5 2.5 0 0 1 2.097 1.249l1.296 2.245a5.5 5.5 0 0 0-3.261-.407l.455-1.438a.5.5 0 0 0-.953-.3l-.659 2.08c-.498.21-.959.492-1.369.832L9.01 3.048A1.5 1.5 0 0 1 10.388 2");
}

</style>
