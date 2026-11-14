<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7q_jkbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beeper-pager" /></template>
<style>
.s7q_jkbuh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 3.5v2.999q1.109.362 1.999 1.252q1.501 1.501 1.501 3.624v4.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 15.625v-4.25q0-2.123 1.501-3.624T7.375 6.25h9.25l.125.001V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146m-2 5.75h-8.5q-2.5 0-2.5 2.5v2.5q0 2.5 2.5 2.5h8.5q1.036 0 1.768-.732t.732-1.768v-2.5q0-1.036-.732-1.768T16.25 9.25");
}

</style>
