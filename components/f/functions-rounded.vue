<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-k842or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:functions-rounded" /></template>
<style>
.cd-k842or {
  fill: currentColor;
  d: path("M13.096 12L7.114 5.935q-.073-.073-.094-.149T7 5.631v-.232q0-.17.116-.285T7.404 5h8.98q.257 0 .437.18q.179.18.179.438q0 .257-.18.444t-.435.188H9.102l5.062 5.179q.228.235.228.567t-.228.575L9.102 17.77h7.283q.256 0 .436.18q.179.18.179.438q0 .257-.18.435q-.179.178-.435.178H7.283q-.117 0-.2-.083t-.083-.2V18.3q0-.066.02-.111t.07-.086z");
}

</style>
