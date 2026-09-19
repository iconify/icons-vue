<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i02zglavz"/><path class="azcznccjk"/><path class="vl_8ng4hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freelancer" /></template>
<style>
.azcznccjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.695 14.142l7.874.352l-2.848-4.289zm0 0l-5.409 10.69l5.249 6.017l5.73-5.697l2.304-10.658zm-7.649 23.653l7.489-6.946l-5.249-6.017z");
}

.i02zglavz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.721 10.205l2.848 4.289L42.5 10.621z");
}

.vl_8ng4hm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 13.502l10.786 11.33l5.409-10.69zm6.529-2.913l1.732 3.239l7.934.314z");
}

</style>
