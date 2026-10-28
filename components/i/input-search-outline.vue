<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjyqlb_or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input-search-outline" /></template>
<style>
.vjyqlb_or {
  fill: currentColor;
  d: path("M5.616 18H5h14zm0 1q-.677 0-1.147-.47T4 17.366v-5.25q0-.69.47-1.152t1.146-.463H9.48v1H5.616q-.25 0-.433.173T5 12.116v5.25q0 .269.183.451t.433.183h12.769q.269 0 .442-.183q.173-.182.173-.451V14.73h1v2.635q0 .696-.472 1.165t-1.162.47zm8.75-15q-1.166 0-1.977.802t-.812 1.967t.812 1.977q.811.812 1.977.812t1.976-.812q.812-.812.812-1.977t-.812-1.967T14.366 4m0-1q1.586 0 2.687 1.091q1.1 1.092 1.1 2.678q0 .656-.196 1.24q-.197.583-.56 1.07l3.188 3.202l-.708.727l-3.188-3.221q-.506.363-1.09.567q-.583.204-1.233.204q-1.587 0-2.688-1.101t-1.101-2.688t1.101-2.678T14.366 3");
}

</style>
