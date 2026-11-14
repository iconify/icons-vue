<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jry3r5bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:creatine" /></template>
<style>
.jry3r5bpl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.224 4.603q-.09.974-.481 1.647H19q2.25 0 2.25 2.25q0 1.5-1 2v8q0 1.346-.952 2.298T17 21.75H7q-1.346 0-2.298-.952T3.75 18.5v-8q-1-.5-1-2q0-2.25 2.25-2.25h.495Q4.75 5.279 4.75 4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h5.915l6.416-1.481q.146-.033.293-.009q.147.025.274.104q.126.079.213.201q.086.121.12.266q.016.072.019.146t-.01.147q-.012.073-.039.142q-.026.069-.065.131q-.039.063-.09.117t-.111.097t-.127.073t-.139.047zm6.526 6.147H5.25v7.75q0 .725.513 1.237q.512.513 1.237.513h10q.725 0 1.237-.513q.513-.512.513-1.237zm-9 1.5h4.5q2.5 0 2.5 2.5v1.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 16.25v-1.5q0-2.5 2.5-2.5");
}

</style>
