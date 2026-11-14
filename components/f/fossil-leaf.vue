<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz_rlpb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fossil-leaf" /></template>
<style>
.nz_rlpb_f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.002 7.439l4.5-4q.103-.091.231-.14q.129-.049.267-.049h10.5q.104 0 .205.029q.1.028.189.083t.16.132q.07.077.117.171l2.5 5q.079.158.079.335v8q0 .162-.067.31t-.189.254l-4 3.5q-.103.09-.23.138q-.128.048-.264.048H6q-.093 0-.182-.023q-.09-.022-.172-.066q-.082-.043-.15-.106q-.069-.062-.12-.139l-3-4.5q-.068-.102-.1-.221t-.025-.242l.5-8q.01-.148.075-.281t.176-.233M6.75 16.5q0 .146.054.28q.055.135.156.24l.01.01q.105.106.243.163t.287.057q10.25 0 10.25-9.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 6.75q-10.25 0-10.25 9.75");
}

</style>
