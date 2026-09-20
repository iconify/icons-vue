<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0udw5_he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-triangle-rounded" /></template>
<style>
.q0udw5_he {
  fill: currentColor;
  d: path("M4.139 19q-.703 0-1.06-.606q-.358-.605.01-1.221L10.95 3.789q.187-.299.467-.457t.58-.159t.584.159t.469.457l7.88 13.384q.368.616.01 1.221q-.357.606-1.06.606zm7.361-5.346v1.442q0 .213.144.357t.357.143t.356-.143t.143-.357v-1.442h1.48q.213 0 .357-.144t.144-.357t-.144-.356t-.356-.143H12.5V11.23q0-.213-.144-.356t-.357-.144t-.356.144t-.143.356v1.423h-1.461q-.213 0-.357.144t-.144.357t.144.356t.356.143z");
}

</style>
