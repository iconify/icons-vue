<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns39-3b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:feather-nature" /></template>
<style>
.ns39-3b-j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.655 13.405q3.991-3.99 3.593-9.955l-.001-.012q-.006-.074-.026-.145t-.054-.137t-.08-.123t-.103-.106q-.056-.047-.121-.083q-.064-.036-.135-.058q-.07-.023-.143-.031q-.074-.009-.147-.002q-5.183.431-8.968 4.217q-.042.041-.076.089q-.035.047-.062.099t-.045.108t-.027.114t-.01.116q0 .059.009.117t.026.114q.018.056.044.108l.314.629l-.996-.199q-.157-.032-.313.004q-.156.035-.284.131q-3.696 2.772-3.797 8.286L15.97 6.97q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-9.699 9.7q6.458-.458 10.324-4.325");
}

</style>
