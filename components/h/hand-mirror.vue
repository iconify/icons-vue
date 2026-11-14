<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf-qacc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-mirror" /></template>
<style>
.bf-qacc8v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 9.5q0-3.386 2.087-5.794Q10.965 1.25 14 1.25t5.163 2.456Q21.25 6.114 21.25 9.5t-2.087 5.794Q17.035 17.75 14 17.75q-2.145 0-3.837-1.226q-.206.553-.759 1.107l-1.945 1.945q-.732.733-1.767.733q-1.036 0-1.768-.733q-.733-.732-.733-1.768q0-1.035.733-1.767l1.945-1.944q.818-.818 1.635-.879Q6.75 11.536 6.75 9.5m7.22-3.53l-3.5 3.5q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l3.5-3.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T14.5 5.75t-.287.057t-.243.163");
}

</style>
