<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnyrorbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-bottom-outline-sharp" /></template>
<style>
.lnyrorbth {
  fill: currentColor;
  d: path("M14.979 10.017Q16.192 8.766 16.192 7V4H7.808v3q0 1.766 1.213 3.017Q10.234 11.27 12 11.27t2.979-1.252M5 21v-1h1.808v-3q0-1.852 1.135-3.285T10.853 12q-1.774-.3-2.91-1.724T6.808 7V4H5V3h14v1h-1.808v3q0 1.852-1.135 3.276T13.147 12q1.774.28 2.91 1.715q1.135 1.433 1.135 3.285v3H19v1z");
}

</style>
