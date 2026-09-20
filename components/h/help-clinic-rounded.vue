<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0gobybja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:help-clinic-rounded" /></template>
<style>
.n0gobybja {
  fill: currentColor;
  d: path("M12.357 16.549q.143-.144.143-.357v-3q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356v3q0 .213.144.357t.357.143t.356-.143m.183-6.24q.23-.23.23-.54t-.23-.54T12 9t-.54.23t-.23.54t.23.539t.54.23t.54-.23M6.616 20q-.667 0-1.141-.475T5 18.386v-8.077q0-.384.172-.727t.474-.565l5.385-4.058q.423-.324.966-.324t.972.324l5.385 4.057q.303.222.474.566q.172.343.172.727v8.077q0 .666-.475 1.14t-1.14.475z");
}

</style>
