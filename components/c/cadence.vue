<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqyflul6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cadence" /></template>
<style>
.nqyflul6e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.106 2.25h3.788q2.708 0 3.295 2.643l2.833 12.75q.351 1.581-.662 2.844t-2.632 1.263H7.272q-1.619 0-2.632-1.263t-.662-2.844l2.833-12.75q.587-2.643 3.295-2.643m2.759 6.002q-2.115.067-2.115 2.248q0 1.711 1.302 2.121l-.789 4.242q-.028.146.003.292t.116.269t.209.205q.125.081.272.108q.072.014.146.013t.146-.016q.073-.016.141-.045t.128-.071t.113-.094q.051-.053.092-.115q.04-.062.067-.131q.028-.068.041-.141l.817-4.387q2.196-.027 2.196-2.25q0-1.761-1.379-2.144l.366-1.969q.028-.146-.003-.292t-.116-.269t-.209-.205t-.272-.108q-.072-.014-.146-.013t-.146.016q-.073.016-.141.045t-.128.071t-.113.094q-.051.053-.092.115q-.04.062-.067.131q-.028.068-.041.141z");
}

</style>
