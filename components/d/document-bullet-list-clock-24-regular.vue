<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k50n4sbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-bullet-list-clock-24-regular" /></template>
<style>
.k50n4sbjw {
  fill: currentColor;
  d: path("m19.414 8.414l-5.829-5.828A2.05 2.05 0 0 0 12.172 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h6.81a6.5 6.5 0 0 1-1.078-1.5H6a.5.5 0 0 1-.5-.5V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5v1.076a6.5 6.5 0 0 1 1.5.422v-1.67a2 2 0 0 0-.586-1.414M13.5 4.621L17.378 8.5H14a.5.5 0 0 1-.5-.5zM10.75 17.5H11q.002.776.174 1.5h-.424a.75.75 0 0 1 0-1.5m.424-1.5c.125-.528.314-1.03.558-1.5h-.982a.75.75 0 0 0 0 1.5zm1.636-3a6.5 6.5 0 0 1 2.186-1.5H10.75a.75.75 0 0 0 0 1.5zm-5.06-1.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M7 15.25a.75.75 0 1 1 1.5 0a.75.75 0 0 1-1.5 0m0 3a.75.75 0 1 1 1.5 0a.75.75 0 0 1-1.5 0m16-.75a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0m-5.78.418a.5.5 0 0 1-.219-.489L17 13.5a.5.5 0 1 1 1 0l.001 3.5h2.496a.5.5 0 0 1 0 1H17.56a.5.5 0 0 1-.34-.082");
}

</style>
