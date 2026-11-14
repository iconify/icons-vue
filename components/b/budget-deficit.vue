<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="socglqbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:budget-deficit" /></template>
<style>
.socglqbgw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 2.25h-.5Q9.5 2.25 9.5 4.5v6q0 .413.076.75H7.629q.121-.35.121-.75v-3q0-.932-.659-1.591T5.5 5.25H5q-2.25 0-2.25 2.25v3q0 .413.076.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h13.826q-.076.337-.076.75v5q0 2.25 2.25 2.25h.5q2.25 0 2.25-2.25v-5q0-.413-.076-.75h.326q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-7.076q.076-.337.076-.75v-6q0-2.25-2.25-2.25");
}

</style>
