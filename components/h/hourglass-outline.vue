<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlbq3vb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-outline" /></template>
<style>
.wlbq3vb_j {
  fill: currentColor;
  d: path("M7.808 20h8.384v-3q0-1.766-1.213-3.017Q13.766 12.73 12 12.73t-2.979 1.252T7.808 17zm7.17-9.983Q16.193 8.765 16.193 7V4H7.808v3q0 1.766 1.213 3.017Q10.234 11.27 12 11.27t2.979-1.252M5 21v-1h1.808v-3q0-1.852 1.135-3.285T10.853 12q-1.774-.3-2.91-1.724T6.808 7V4H5V3h14v1h-1.808v3q0 1.852-1.135 3.276T13.147 12q1.774.28 2.91 1.715q1.135 1.433 1.135 3.285v3H19v1zm7-17");
}

</style>
