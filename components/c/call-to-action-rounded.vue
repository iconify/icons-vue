<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg01cpb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-to-action-rounded" /></template>
<style>
.wg01cpb5d {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zM7.5 16.5h9q.414 0 .707-.293t.293-.707t-.293-.707t-.707-.293h-9q-.413 0-.707.293T6.5 15.5t.293.707t.707.293");
}

</style>
