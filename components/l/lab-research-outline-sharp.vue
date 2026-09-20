<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw3xnrbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lab-research-outline-sharp" /></template>
<style>
.bw3xnrbow {
  fill: currentColor;
  d: path("M8.48 15.98v-1h1.695q-.067.25-.105.491q-.037.24-.045.51zM8.347 21q-1.805 0-3.076-1.241T4 16.73V7.654H2.346V3h12v4.654h-1.673v3.737q-.235.163-.437.346t-.384.398H8.481v-1h3.192V7.654H5v9.077q0 1.384.98 2.327T8.347 20q.654 0 1.219-.229q.564-.229 1.008-.63q.104.25.229.459t.283.423q-.56.458-1.252.717q-.692.26-1.487.26m-5-14.346h10V4h-10zM18.16 18.487q.82-.821.82-1.987t-.82-1.986q-.821-.822-1.987-.822q-1.165 0-1.986.822q-.821.82-.821 1.986t.82 1.987t1.987.82q1.166 0 1.987-.82m3.113 3.802l-2.777-2.777q-.511.388-1.102.592q-.59.204-1.221.204q-1.586 0-2.697-1.111t-1.11-2.697t1.11-2.697t2.697-1.11t2.697 1.11t1.11 2.697q0 .63-.203 1.221q-.204.59-.592 1.102l2.777 2.777zM3.346 6.653V4z");
}

</style>
