<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9fim4bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:decision-tree" /></template>
<style>
.y9fim4bqx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 1.75h-2.5q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h.5v1.743q-.465.161-.841.538l-.878.878q-.377.376-.538.841H5.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.75 12v4.25h-.5q-1.036 0-1.768.732T1.75 18.75v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-2.5-2.5-2.5h-.5v-3.5h2.743q.161.465.538.841l.878.878q.659.66 1.591.66t1.591-.66l.878-.878q.377-.376.538-.841h2.743v3.5h-.5q-2.5 0-2.5 2.5v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768t-1.768-.732h-.5V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.493q-.161-.465-.538-.841l-.878-.878q-.376-.377-.841-.538V7.25h.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768T13.25 1.75");
}

</style>
