<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bps_tebdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-drink-rounded" /></template>
<style>
.bps_tebdt {
  fill: currentColor;
  d: path("M6.975 22q-.775 0-1.337-.513T5 20.226L3.275 4.475q-.125-1 .55-1.737T5.5 2h13q1 0 1.675.738t.55 1.737L19 20.225q-.075.75-.638 1.263T17.026 22zM5.65 8h12.7l.4-4H5.25zm8.375 10.175q.825-.825.825-2.025q0-1.175-.687-2.275t-1.388-1.95q-.15-.2-.363-.288T12 11.55t-.413.088t-.362.287q-.7.85-1.387 1.95T9.15 16.15q0 1.2.825 2.025T12 19t2.025-.825");
}

</style>
