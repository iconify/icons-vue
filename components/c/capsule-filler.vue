<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilwijubms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capsule-filler" /></template>
<style>
.ilwijubms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.044 1.75H7.955q-1.703.001-2.325 1.587q-.622 1.585.626 2.745l3.175 2.949q.319.296.319.732v.487q0 2 2 2h.5q2 0 2-2v-.487q0-.436.319-.732l3.176-2.95q1.247-1.159.625-2.744T16.044 1.75M9.25 14.5V18q0 2.75 2.75 2.75q1.139 0 1.945-.805q.805-.806.805-1.945v-3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V18q0 1.76-1.245 3.005T12 22.25t-3.005-1.245T7.75 18v-3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
