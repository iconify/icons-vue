<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qv-ajb5_g"/><circle class="thgnwkk8s"/><circle class="o3dh8sbgq"/><path class="q_bqpwgyr"/><path class="hum3yv15x"/><path class="xukiwubsa"/><path class="vyft6hbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:direct-hit" /></template>
<style>
.hum3yv15x {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M36.587 29.22c0 4.229-3.426 7.659-7.653 7.659a7.66 7.66 0 0 1-7.658-7.659a7.653 7.653 0 0 1 7.658-7.652a7.65 7.65 0 0 1 7.653 7.652");
}

.o3dh8sbgq {
  cx: 28.932px;
  cy: 29.31px;
  r: 17.813px;
  fill: var(--svg-color--be1e2d, #be1e2d);
}

.q_bqpwgyr {
  fill: var(--svg-color--fff, #fff);
  d: path("M42.33 29.661c0 7.405-6 13.403-13.399 13.403c-7.404 0-13.4-5.998-13.4-13.403c0-7.398 5.996-13.398 13.4-13.398c7.399 0 13.399 5.999 13.399 13.398");
}

.qv-ajb5_g {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M57.864 28.882c0 15.977-12.955 28.93-28.93 28.93C12.955 57.812 0 44.859 0 28.882C0 12.903 12.955-.05 28.934-.05c15.975 0 28.93 12.953 28.93 28.932");
}

.thgnwkk8s {
  cx: 28.934px;
  cy: 29.458px;
  r: 23.569px;
  fill: var(--svg-color--fff, #fff);
}

.vyft6hbst {
  fill: var(--svg-color--226798, #226798);
  d: path("M59.26 59.95c.668-.721.361-2.1-.697-3.091l-29.23-27.324a2.9 2.9 0 0 1-1.426 1.471c-.479.232-.983.378-1.499.518a.6.6 0 0 0-.13.032l29.86 27.904c1.052.984 2.453 1.203 3.124.49");
}

.xukiwubsa {
  fill: var(--svg-color--71a3b9, #71a3b9);
  d: path("M56.21 61.63c.837-.547-3.648-5.855-3.959-6.185l-16.04-14.951c-.31-.325-.191-1.257-1.026-.695c-.835.556-1.259 1.271-.943 1.594l15.14 22.478c.32.332 6.01-1.674 6.834-2.241M38.29 38.26l16 14.994c.347.291 5.945 4.408 6.441 3.535c.505-.864 2.122-6.681 1.771-6.969L39.054 36.226c-.341-.285-1.025.186-1.522 1.056c-.505.867.411.69.754.978");
}

</style>
