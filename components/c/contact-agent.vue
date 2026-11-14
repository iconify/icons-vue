<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqt8e7bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contact-agent" /></template>
<style>
.wqt8e7bdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.702 2.702Q1.75 3.654 1.75 5v10q0 3.25 3.25 3.25h.75V21q0 .125.041.243q.04.119.117.217q.045.059.101.107t.12.085q.064.036.135.06q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.053q.066-.033.124-.078l4.297-3.342H19q3.25 0 3.25-3.25V5q0-1.346-.952-2.298T19 1.75H5q-1.346 0-2.298.952m4.707 6.829l3-3q.659-.66 1.591-.66t1.591.66l.409.408V6.75q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T14.75 6t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.689l1.091 1.092q.659.659.659 1.59V13q0 2.25-2.25 2.25H9q-2.25 0-2.25-2.25v-1.879q0-.931.658-1.59z");
}

</style>
