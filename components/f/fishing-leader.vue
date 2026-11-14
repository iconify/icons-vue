<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtawpac1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-leader" /></template>
<style>
.mtawpac1f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 5.5q0-3.25 3.25-3.25t3.25 3.25q0 2.85-2.5 3.201V17q0 1.864-1.318 3.182T10.25 21.5t-3.182-1.318T5.75 17v-2.5q0-.147.055-.283t.158-.24v-.001l.006-.006h.001q.105-.106.243-.163t.287-.057t.287.057t.243.163h.001l1.999 2q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-.72-.719V17q0 3 3 3q1.243 0 2.121-.879q.879-.878.879-2.121V8.701q-2.5-.351-2.5-3.201");
}

</style>
