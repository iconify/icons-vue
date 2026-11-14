<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdv_g6ckk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:back-soon-sign" /></template>
<style>
.rdv_g6ckk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3.5v3.75h4.5V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.75H16q1.76 0 3.005 1.245T20.25 11.5v5q0 1.76-1.245 3.005T16 20.75H8q-1.76 0-3.005-1.245T3.75 16.5v-5q0-1.76 1.245-3.005T8 7.25h.25V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q8.926 2.75 9 2.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146M12 10.25q-3.75 0-3.75 3.75T12 17.75T15.75 14T12 10.25");
}

</style>
