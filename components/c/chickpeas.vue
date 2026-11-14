<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuo22nlds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chickpeas" /></template>
<style>
.xuo22nlds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 6.75q0-3 3-3t3 3q0 .574-.11 1.038q1.143.146 1.732.845l.006-.005q.879-.88 2.122-.88t2.122.88t.878 2.121q.001.832-.392 1.501H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q-.001 3.457-2.907 5.878q-2.845 2.369-6.843 2.369t-6.843-2.369Q2.251 16.457 2.25 13q0-.074.014-.146t.043-.141q.028-.068.069-.129q.041-.062.093-.114q.053-.052.114-.093t.13-.07t.14-.043q.073-.014.147-.014h1.757q-.257-.621-.257-1.5q0-2.661 2.36-2.962q-.11-.464-.11-1.038");
}

</style>
