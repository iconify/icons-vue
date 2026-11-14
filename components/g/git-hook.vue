<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn54g9rrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-hook" /></template>
<style>
.dn54g9rrg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 4.25q0-2.75 2.75-2.75t2.75 2.75q0 2.345-2 2.69V14q0 2.589-1.831 4.419Q13.589 20.25 11 20.25t-4.419-1.831Q4.75 16.589 4.75 14v-4q0-.147.055-.283t.158-.24v-.001l.006-.006h.001q.105-.106.243-.163T5.5 9.25t.287.057t.243.163h.001l2.999 3q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-1.72-1.719V14q0 1.968 1.391 3.359T11 18.75t3.359-1.391T15.75 14V6.94q-2-.345-2-2.69");
}

</style>
