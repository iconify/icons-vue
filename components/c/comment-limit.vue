<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuqrkbbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:comment-limit" /></template>
<style>
.tuqrkbbnr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5q0-1.346.952-2.298T5 1.75h14q1.346 0 2.298.952T22.25 5v10q0 .974-.292 1.656l-.056-.058q-.196-.196-.407-.357Q21.368 13 18 13q-3.238 0-3.48 2.995q-1.177.672-1.443 2.255h-1.795l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5q-3.25 0-3.25-3.25zm19.268 12.482q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
