<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip5nvcb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dm-limit" /></template>
<style>
.ip5nvcb_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5q0-1.346.952-2.298T5 1.75h13.5q1.346 0 2.298.952T21.75 5v8.5q0 .055-.002.108q-.24-.404-.596-.76q-1.099-1.098-2.652-1.098q-3.687 0-3.749 3.626q-.939.435-1.374 1.374h-3.095l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5q-3.25 0-3.25-3.25zm20.268 11.982q-.452-.451-1.018-.624V15.5q0-1.036-.732-1.768T18.5 13Q16 13 16 15.5v.817q-1.75.341-1.75 2.433v1q0 1.036.732 1.768t1.768.732h3.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768M17.5 15.5v.75h2v-.75q0-.414-.293-.707T18.5 14.5q-1 0-1 1m-1.75 4.25v-1q0-1 1-1h3.5q1 0 1 1v1q0 .414-.293.707t-.707.293h-3.5q-.414 0-.707-.293t-.293-.707");
}

</style>
