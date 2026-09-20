<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i_3pa4aaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-starburst-16-filled" /></template>
<style>
.i_3pa4aaj {
  fill: currentColor;
  d: path("M8.006.019a.5.5 0 0 1 .396.194l1.293 1.676a.5.5 0 0 0 .537.174l2.03-.595a.5.5 0 0 1 .641.465l.062 2.116a.5.5 0 0 0 .331.456l1.994.712a.5.5 0 0 1 .244.753L14.34 7.718a.5.5 0 0 0 0 .564l1.194 1.748a.5.5 0 0 1-.245.753l-1.993.712a.5.5 0 0 0-.331.456l-.062 2.116a.5.5 0 0 1-.64.465l-2.031-.595a.5.5 0 0 0-.537.175l-1.293 1.675a.5.5 0 0 1-.792 0l-1.293-1.676a.5.5 0 0 0-.537-.174l-2.031.595a.5.5 0 0 1-.64-.465l-.062-2.116a.5.5 0 0 0-.331-.456l-1.994-.712a.5.5 0 0 1-.244-.753l1.194-1.748a.5.5 0 0 0 0-.564L.478 5.97a.5.5 0 0 1 .244-.753l1.994-.712a.5.5 0 0 0 .331-.456l.062-2.116a.5.5 0 0 1 .64-.465l2.031.595a.5.5 0 0 0 .537-.174L7.61.213a.5.5 0 0 1 .396-.194M8 4.5a.5.5 0 0 0-.5.5v2.5H5a.5.5 0 0 0 0 1h2.5V11a.5.5 0 0 0 1 0V8.5H11a.5.5 0 0 0 0-1H8.5V5a.5.5 0 0 0-.5-.5");
}

</style>
