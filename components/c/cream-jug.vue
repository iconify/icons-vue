<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdmk7il6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cream-jug" /></template>
<style>
.rdmk7il6w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 4.375q-1.508 0-2.446 2.346q-.068.169-.051.35l1 10.5l.004.028Q7.677 20.75 11 20.75h2q3.323 0 3.743-3.151l.004-.028l.222-2.336q3.156-.203 3.156-3.235q0-2.931-2.541-3.219l.163-1.71q.003-.035.003-.071q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 6.25h-6.009q-.893-1.875-2.241-1.875m.527 1.875H8.223q.273-.375.527-.375t.527.375m7.838 7.457l.325-3.42q1.185.219 1.185 1.713q0 1.475-1.51 1.707");
}

</style>
