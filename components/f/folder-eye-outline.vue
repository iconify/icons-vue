<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bszt-ubxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-eye-outline" /></template>
<style>
.bszt-ubxl {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v5.723q-.238-.178-.488-.316T20 13.75V8.616q0-.27-.173-.443T19.385 8h-8.19l-2-2h-4.58q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173h3.173v1zm11.519 3q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.382-.94t3.383.94T22 18.538q-.933 1.581-2.483 2.521q-1.55.941-3.382.941m2.62-1.67q1.234-.668 2.072-1.791q-.838-1.123-2.072-1.793t-2.62-.669t-2.62.67t-2.073 1.792q.839 1.123 2.073 1.792t2.62.669t2.62-.67m-3.327-1.085q-.294-.293-.294-.707t.294-.706q.293-.294.707-.294q.413 0 .706.294t.294.706t-.294.707t-.706.293t-.707-.293M4 18V6v7.733v-1.04z");
}

</style>
