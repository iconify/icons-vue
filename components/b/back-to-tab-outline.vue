<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gafa07brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:back-to-tab-outline" /></template>
<style>
.gafa07brw {
  fill: currentColor;
  d: path("M9.525 12.239L4 6.714v3.902H3V5h5.616v1H4.689l5.55 5.525zM4.615 19q-.69 0-1.153-.462T3 17.384V13h1v4.385q0 .269.173.442t.443.173h7.153v1zM20 12.77V6.615q0-.27-.173-.443T19.385 6H11V5h8.385q.69 0 1.153.463T21 6.616v6.153zm1 2.384V19h-6.846v-3.846z");
}

</style>
