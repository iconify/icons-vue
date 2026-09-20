<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk3qmybhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-split-rounded" /></template>
<style>
.wk3qmybhz {
  fill: currentColor;
  d: path("M6 6.708V9.5q0 .214-.143.357T5.5 10t-.357-.143T5 9.5V5.808q0-.348.23-.578T5.808 5H9.5q.214 0 .357.143T10 5.5t-.143.357T9.5 6H6.708l5.313 5.314q.218.217.348.522q.131.305.131.628V18.5q0 .214-.143.357T12 19t-.357-.143t-.143-.357v-6.042q0-.116-.039-.221t-.134-.202zm12 0l-3.488 3.494q-.146.146-.347.156t-.367-.156t-.165-.36t.165-.36L17.292 6H14.5q-.213 0-.357-.143T14 5.5t.143-.357T14.5 5h3.692q.349 0 .578.23t.23.578V9.5q0 .214-.143.357T18.5 10t-.357-.143T18 9.5z");
}

</style>
