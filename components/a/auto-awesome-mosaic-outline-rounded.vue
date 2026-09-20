<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5_vw-wfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-awesome-mosaic-outline-rounded" /></template>
<style>
.q5_vw-wfy {
  fill: currentColor;
  d: path("M11 20H5.616q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4H11zm-1-1V5H5.616q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173zm3-8V4h5.385q.69 0 1.152.463T20 5.616V11zm1-1h5V5.616q0-.27-.173-.443T18.385 5H14zm-1 10v-7h7v5.385q0 .69-.462 1.152T18.384 20zm1-1h4.385q.269 0 .442-.173t.173-.442V14h-5zm0-5");
}

</style>
