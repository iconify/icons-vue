<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtis2ybqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-crown" /></template>
<style>
.xtis2ybqm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2.25q-5.25 0-5.25 8.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.833l.922 7.838l.005.035q.292 1.752 1.865 1.752q1.563 0 1.861-1.731l.993-4.466Q11.035 15 12 15t1.021.178l.993 4.466q.298 1.731 1.861 1.731q1.573 0 1.865-1.752l.005-.035l.922-7.838H20.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-8.75-5.25-8.75q-1.3 0-2.726.958q-.806.542-1.274.542t-1.274-.542Q9.3 2.25 8 2.25m-.257 17.143l-.9-7.643h10.314l-.9 7.643q-.085.482-.382.482q-.302 0-.385-.498l-.008-.04l-1-4.5l-.004-.019Q14.148 13.5 12 13.5t-2.478 1.318l-.004.019l-1 4.5l-.008.04q-.083.498-.385.498q-.297 0-.382-.482");
}

</style>
