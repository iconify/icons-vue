<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv-o90xlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flotation-cell" /></template>
<style>
.kv-o90xlf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.75q3 0 3 3q0 .574-.11 1.038q2.36.301 2.36 2.962q0 .879-.257 1.5h3.257V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T21 7.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v10.5q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 7.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146v3.25h3.257q-.257-.621-.257-1.5q0-2.661 2.36-2.962Q9 6.324 9 5.75q0-3 3-3M3.75 18.5q0 1.25 1.25 1.25h14q1.25 0 1.25-1.25v-5.75H3.75z");
}

</style>
