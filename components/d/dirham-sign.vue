<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-hexl5ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dirham-sign" /></template>
<style>
.x-hexl5ip {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 3.25 7 3.25h4q3.693 0 5.986 2.457Q18.468 7.295 18.98 9.5H6.25zm0 7h12.96q.04.487.04 1t-.04 1H6.25zm0 3.5V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q3.693 0 5.986-2.457q1.482-1.588 1.994-3.793z");
}

</style>
