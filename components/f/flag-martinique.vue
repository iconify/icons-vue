<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pf_6pj_zy"/><path class="t3inkcb4s"/><path class="o2b-fobdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:flag-martinique" /></template>
<style>
.o2b-fobdb {
  fill: var(--svg-color--e20613, #E20613);
  d: path("M4 34v60l44.4-30z");
}

.pf_6pj_zy {
  fill: var(--svg-color--009540, #009540);
  d: path("M4 34h120v30H4z");
}

.t3inkcb4s {
  fill: var(--svg-color--1d1d1b, #1D1D1B);
  d: path("M4 64h120v30H4z");
}

</style>
