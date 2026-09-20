<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgm50c91m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-eye-outline-sharp" /></template>
<style>
.mgm50c91m {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v7.339q-.238-.178-.488-.316T20 13.75V8h-8.806l-2-2H4v12h3.789v1zm13.135 3q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.383-.94t3.382.94T22 18.538q-.933 1.581-2.483 2.521q-1.55.941-3.382.941m2.62-1.67q1.234-.668 2.072-1.791q-.838-1.123-2.072-1.793t-2.62-.669t-2.62.67t-2.073 1.792q.839 1.123 2.073 1.792t2.62.669t2.62-.67m-3.327-1.085q-.294-.293-.294-.707t.294-.706q.293-.294.707-.294q.413 0 .706.294t.294.706t-.294.707t-.706.293t-.707-.293M4 18V6v7.733v-1.04z");
}

</style>
