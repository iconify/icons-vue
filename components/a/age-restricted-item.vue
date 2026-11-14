<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5189vbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:age-restricted-item" /></template>
<style>
.n5189vbwo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M9.05 7.4q.119-.09.264-.127q.144-.037.292-.015t.276.097t.218.195q.073.097.112.213q.038.115.038.237v8q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 16V9.5l-.8.6q-.119.09-.264.127q-.144.037-.292.015t-.276-.097T6.9 9.95q-.044-.059-.076-.126q-.032-.066-.051-.138q-.018-.071-.022-.145t.007-.147t.034-.143q.025-.07.063-.133q.037-.064.087-.119T7.05 8.9zm5.45-.15q1.036 0 1.768.732T17 9.75q0 .869-.516 1.524q1.016.73 1.016 2.476q0 3-3 3t-3-3q0-1.649.906-2.391Q12 10.757 12 9.75q0-2.5 2.5-2.5");
}

</style>
