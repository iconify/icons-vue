<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hixuzydyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-arrow-outline-rounded" /></template>
<style>
.hixuzydyv {
  fill: currentColor;
  d: path("M12.525 18.025q-.5.325-1.012.038T11 17.175V13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h8V6.825q0-.6.513-.888t1.012.038l8.15 5.175q.475.3.475.85t-.475.85zM13 15.35L18.275 12L13 8.65zM13 12");
}

</style>
