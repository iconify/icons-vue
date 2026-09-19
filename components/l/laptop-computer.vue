<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ss7-dc6xw"/><path class="o0q02083u"/><path class="i1evl0bhk"/><path class="l9gecvb2o"/><path class="m8guaib5n"/><circle class="kg8vc2lwr"/><path class="g5pydwb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:laptop-computer" /></template>
<style>
.g5pydwb3g {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M36.3 60.8h-8.6c-.3 0-1.1 0-1.1-1h10.8c0 1-.8 1-1.1 1");
}

.i1evl0bhk {
  fill: var(--svg-color--bfbebe, #bfbebe);
  d: path("M55.3 54.2H8.7l-1.7 2h50z");
}

.kg8vc2lwr {
  cx: 32px;
  cy: 19.6px;
  r: 0.8px;
  fill: var(--svg-color--ddd, #ddd);
}

.l9gecvb2o {
  fill: var(--svg-color--212528, #212528);
  d: path("M37.1 57.1H26.9l-.8 1.1h11.8z");
}

.m8guaib5n {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M9 21h46v29.8H9z");
}

.o0q02083u {
  fill: var(--svg-color--ddd, #ddd);
  d: path("M57 53.8H7l-5 4.9h60z");
}

.ss7-dc6xw {
  fill: var(--svg-color--212528, #212528);
  d: path("M7.3 53.8h49.4c.8 0 1.4-.6 1.4-1.4v-33c0-.8-.6-1.4-1.4-1.4H7.3c-.7 0-1.3.6-1.3 1.4v33c0 .8.6 1.4 1.3 1.4M2 58.7C2 60.3 3.3 62 5 62h54c1.6 0 3-1.7 3-3.3z");
}

</style>
