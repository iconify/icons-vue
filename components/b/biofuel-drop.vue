<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpqt-gbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:biofuel-drop" /></template>
<style>
.dpqt-gbqg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.166 4.069Q13.112 2.733 12.6 2.05q-.064-.086-.15-.15q-.059-.044-.126-.076q-.066-.032-.138-.051q-.071-.018-.145-.022t-.147.007t-.143.034q-.07.025-.133.063q-.064.037-.119.087t-.099.108q-.512.683-1.566 2.019Q4.75 10.516 4.75 14.5q0 3.003 2.123 5.127T12 21.75t5.127-2.123q2.123-2.124 2.123-5.127q0-3.984-5.084-10.431M8.25 17.25q0-6 6.75-6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 6-6.75 6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
