<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkerfuiiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:conte-crayon" /></template>
<style>
.wkerfuiiw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.126 4.167q-.732-.733-1.767-.733q-1.036 0-1.768.733l-7.424 7.424q-.733.732-.733 1.767q0 1.036.733 1.768l.707.707q.732.733 1.768.733q1.035 0 1.767-.733l7.424-7.424q.733-.732.733-1.768q0-1.035-.733-1.767zM5 17.5q-1.561 0-3.03 1.47q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163q1.97-1.969 3.94 0Q8.439 21.5 10 21.5t3.03-1.47q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-1.97 1.969-3.94 0Q6.561 17.5 5 17.5");
}

</style>
