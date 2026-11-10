<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w3sg6tpvz"/><path class="ybz2sib2r"/><path class="vmg5_2jyg"/><path class="ymb5p1mfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hubspace" /></template>
<style>
.vmg5_2jyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.144 23.973c.874-2.387 3.168-4.093 5.856-4.093s4.982 1.706 5.856 4.093");
}

.w3sg6tpvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.11 39.97V29.802l4.89-3.61l4.89 3.61V39.97");
}

.ybz2sib2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.766 31.302h2.468v2.468h-2.468zM5.5 23.973C6.836 14.957 14.616 8.03 24 8.03s17.164 6.927 18.5 15.943");
}

.ymb5p1mfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.838 23.973c1.258-5.555 6.229-9.708 12.162-9.708s10.904 4.153 12.162 9.708");
}

</style>
