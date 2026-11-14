<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2-7d8byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:average-speed-check" /></template>
<style>
.q2-7d8byq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25h-4.5q-3.25 0-3.25 3.25t3.25 3.25h3.25V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8.745q3-.123 3-3.245q0-1.346-.952-2.298T19 2.25M1.75 15.75q0-1.808 1.731-2.327l.739-.221q.322-.097.52-.37l1.129-1.552q.749-1.03 2.022-1.03h2.718q1.273 0 2.022 1.03l1.145 1.575q.189.259.493.36l.594.199q1.637.545 1.637 2.272v.064q0 1.564-1.224 1.905q.224.561.224 1.345q0 2.75-2.75 2.75T10 19q0-.719.188-1.25H8.312q.188.531.188 1.25q0 2.75-2.75 2.75T3 19q0-.749.204-1.293q-1.454-.252-1.454-1.957");
}

</style>
