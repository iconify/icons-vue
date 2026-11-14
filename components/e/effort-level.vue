<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbdcb27ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:effort-level" /></template>
<style>
.sbdcb27ml {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.495 8.995q-.464.464-.755 1q-.498-.245-1.24-.245H4q-2.25 0-2.25 2.25T4 14.25h6.5q.742 0 1.24-.245q.291.536.755 1Q13.74 16.25 15.5 16.25t3.005-1.245q.971-.971 1.185-2.255h1.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.81q-.214-1.284-1.185-2.255Q17.26 7.75 15.5 7.75t-3.005 1.245");
}

</style>
