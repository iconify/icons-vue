<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezkpcacsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-sharp" /></template>
<style>
.ezkpcacsm {
  fill: currentColor;
  d: path("M12.725 17.275Q12 16.55 12 15.5t.725-1.775T14.5 13t1.775.725T17 15.5t-.725 1.775T14.5 18t-1.775-.725M3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
