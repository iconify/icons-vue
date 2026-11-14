<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9wyqpurt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-draft" /></template>
<style>
.l9wyqpurt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h7.253q-.336-.245-.672-.581q-2.474-2.474 0-4.949l3.889-3.889q1.39-1.39 2.78-1.218V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zm7.504 11.745q1.591 1.591 0 3.181l-3.889 3.889q-1.591 1.591-3.181 0t0-3.181l3.889-3.889q1.591-1.591 3.181 0m-1.06 1.06q-.531-.53-1.061 0l-3.889 3.889q-.53.531 0 1.061t1.061 0l3.889-3.889q.53-.53 0-1.061m-1.177 6.523q-.542.542-1.212.776q.222-.183.444-.405l1.521-1.521q-.236.633-.753 1.15");
}

</style>
