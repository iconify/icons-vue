<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9e9_7mrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gymnastic-rings" /></template>
<style>
.u9e9_7mrp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.818 12.318q1.045-1.045 2.432-1.261V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 1.75 7 1.75t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.557q1.387.216 2.432 1.261Q11.5 13.636 11.5 15.5t-1.318 3.182T7 20t-3.182-1.318T2.5 15.5t1.318-3.182m12.432-1.261q-1.387.216-2.432 1.261Q12.5 13.636 12.5 15.5t1.318 3.182T17 20t3.182-1.318T21.5 15.5t-1.318-3.182q-1.045-1.045-2.432-1.261V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 1.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146z");
}

</style>
