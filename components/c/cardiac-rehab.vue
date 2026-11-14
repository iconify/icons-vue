<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6cw_cb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cardiac-rehab" /></template>
<style>
.l6cw_cb4a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.851 4.851q-1.24 1.24-1.52 2.898Q3.26 7 4.5 7q3.24 0 3.481 3h8.038q.241-3 3.481-3q1.3 0 2.117.483q-.329-1.493-1.468-2.632Q18.548 3.25 16.25 3.25q-2.621 0-4.25 1.953Q10.371 3.25 7.75 3.25q-2.298 0-3.899 1.601M6.75 10.5q0-2.25-2.25-2.25q-.932 0-1.591.659T2.25 10.5v3q0 2.25 2.25 2.25t2.25-2.25v-.75h10.5v.75q0 2.25 2.25 2.25t2.25-2.25v-3q0-2.25-2.25-2.25t-2.25 2.25v.75H6.75zm-3 0q0-.75.75-.75t.75.75v3q0 .75-.75.75t-.75-.75zm15.75-.75q-.75 0-.75.75v3q0 .75.75.75t.75-.75v-3q0-.75-.75-.75m-7.891 10.89q-2.315-1.414-4.62-3.56q-.262-.244-.51-.486q1.35-.698 1.502-2.594h8.038q.152 1.896 1.502 2.594q-.248.242-.51.486q-2.305 2.146-4.62 3.56q-.088.054-.188.082q-.099.028-.203.028t-.203-.028t-.188-.082");
}

</style>
