<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w057zkg5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:daypack" /></template>
<style>
.w057zkg5f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.98 6.329q.796.486 1.5 1.191q2.27 2.27 2.27 5.48v1.5q0 3.21-2.27 5.48T12 22.25t-5.48-2.27t-2.27-5.48V13q0-3.21 2.27-5.48q.704-.705 1.5-1.191Q8 6.414 8 6.5v6.778q-.203.146-.389.333q-.861.86-.861 2.077v.625q.001 2.937 2.938 2.937h4.625q2.936-.001 2.937-2.937v-.625q0-1.916-1.25-2.582V6.5q0-.086-.02-.171m-1.023-.519q-.226-.093-.457-.17v-.89q0-1.036-.732-1.768T12 2.25q-2.5 0-2.5 2.5v.89q-.231.077-.457.17q.102.043.187.114q.085.07.146.162t.092.198t.032.216v6.255q.093-.005.188-.005h4.625q.095 0 .187.003V6.5q0-.11.032-.216t.092-.198t.146-.162t.187-.114M11 5.308V4.75q0-1 1-1q.414 0 .707.293T13 4.75v.558q-.488-.058-1-.058t-1 .058");
}

</style>
