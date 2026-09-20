<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="crscedbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-down-16-regular" /></template>
<style>
.crscedbjv {
  fill: currentColor;
  d: path("M4.136 6.571A1 1 0 0 1 4.956 5h6.087a1 1 0 0 1 .82 1.571l-2.632 3.784a1.5 1.5 0 0 1-2.462 0zM4.956 6L7.59 9.784a.5.5 0 0 0 .821 0L11.043 6z");
}

</style>
