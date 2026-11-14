<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9r0svhjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:document-lock" /></template>
<style>
.e9r0svhjf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h6.954Q13 21.198 13 19.75v-1q0-2.172 1.258-3.086q.164-3.414 3.742-3.414q1.279 0 2.25.745V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zm6.987 15.012q-.243-.242-.518-.404V16q0-1.036-.732-1.768T18 13.5q-2.5 0-2.5 2.5v.464q-1.25.518-1.25 2.286v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768M19 16.25h-2V16q0-1 1-1q.414 0 .707.293T19 16zm-3.25 2.5q0-1 1-1h2.5q1 0 1 1v1q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707zm1.25.75V19h2v.5z");
}

</style>
