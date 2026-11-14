<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzbc7fb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:butter-lamp" /></template>
<style>
.wzbc7fb1v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.551 1.991Q15 4.644 15 6.625q0 2.188-2.712 3.317Q12.15 10 12 10t-.288-.058Q9 8.813 9 6.625q0-1.981 2.449-4.634q.05-.054.11-.097q.059-.044.127-.075q.067-.031.138-.048t.146-.02q.074-.003.147.008q.073.012.142.037q.069.026.132.064t.118.089q.022.02.042.042M20 11.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 5.675-6.186 6.579l.015.035l.36.841q.426.992-.168 1.894q-.595.902-1.675.901h-2.192q-1.08.001-1.675-.901q-.594-.902-.168-1.894v-.001l.36-.84l.015-.035Q3.25 17.675 3.25 12q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 11.25z");
}

</style>
