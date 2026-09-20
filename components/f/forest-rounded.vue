<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le08ft6nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forest-rounded" /></template>
<style>
.le08ft6nc {
  fill: currentColor;
  d: path("M14 20.192V17.77h2v2.5q0 .31-.21.52q-.211.211-.52.211h-.462q-.349 0-.578-.23t-.23-.578m-6 0V17H3.383q-.485 0-.712-.429t.04-.833L5.85 11h-.385q-.478 0-.718-.426t.053-.83l3.529-5.069q.13-.18.307-.264q.178-.084.364-.084t.364.084q.176.083.307.264l3.529 5.07q.292.403.053.829q-.24.426-.718.426h-.385l3.144 4.739q.267.403.04.832q-.226.429-.711.429H10v3.27q0 .309-.21.52q-.211.21-.52.21h-.462q-.349 0-.578-.23T8 20.192M17.039 17l-3.462-5.23H14q.485 0 .724-.433q.24-.431-.053-.835l-2.2-3.135l1.858-2.692q.13-.18.307-.264q.178-.084.364-.084t.364.084q.176.083.307.264l3.529 5.07q.292.403.053.829q-.24.426-.718.426h-.385l3.139 4.739q.267.403.04.832t-.712.429z");
}

</style>
