<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-bpsqb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:joystick" /></template>
<style>
.k-bpsqb8h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.995 3.495Q7.75 4.74 7.75 6.5t1.245 3.005q.971.971 2.255 1.185v3.56H7q-1.875 0-2.812.938q-.938.937-.938 2.812q0 3.75 3.75 3.75h10q3.75 0 3.75-3.75T17 14.25h-4.25v-3.56q1.284-.214 2.255-1.185Q16.25 8.26 16.25 6.5t-1.245-3.005T12 2.25T8.995 3.495M16.01 17.25q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H16q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T15.25 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
