<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si-b1dbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:force-pull" /></template>
<style>
.si-b1dbvx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 6.25h2q1.76 0 3.005 1.245T12.25 10.5v1.171q.699.492 1.978-.307q2.335-1.46 3.832-.114h1.129L17.47 9.53q-.106-.105-.163-.243T17.25 9t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T18 8.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094l3 3l.004.003q.104.105.16.242t.056.285t-.057.287t-.163.243l-3 3q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T17.25 15t.057-.287t.163-.243l1.719-1.72H17.75q-.159 0-.305-.065t-.252-.183q-.704-.782-2.171.134q-1.577.986-2.772.692v.172q0 1.76-1.245 3.005T8 17.75H6q-1.76 0-3.005-1.245T1.75 13.5v-3q0-1.76 1.245-3.005T6 6.25");
}

</style>
