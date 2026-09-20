<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hkz1abbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-up-16-regular" /></template>
<style>
.hkz1abbqb {
  fill: currentColor;
  d: path("M4.136 9.427a1 1 0 0 0 .82 1.571h6.087a1 1 0 0 0 .82-1.571L9.232 5.643a1.5 1.5 0 0 0-2.462 0zm.82.571L7.59 6.214a.5.5 0 0 1 .821 0l2.633 3.784z");
}

</style>
