<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tq-ho8bpv"/><path class="ur9fzcb2z"/><path class="wyr8oddun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dndsync" /></template>
<style>
.tq-ho8bpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.35 24h11.3M22.054 4.5l-5.423 5.423l5.423 5.423");
}

.ur9fzcb2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.852 31.6a14 14 0 0 0 2.225-7.6c0-7.775-6.302-14.077-14.077-14.077h-7.37M25.946 43.5l5.423-5.423l-5.423-5.423");
}

.wyr8oddun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.148 16.4A14 14 0 0 0 9.923 24c0 7.775 6.302 14.077 14.077 14.077h7.37");
}

</style>
