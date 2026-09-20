<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1zpc0bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-home-outline-rounded" /></template>
<style>
.w1zpc0bgi {
  fill: currentColor;
  d: path("m12.97 4.958l5.384 4.058q.298.217.472.565t.174.727v8.077q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 19.056 5 18.385v-8.077q0-.38.174-.727t.472-.565l5.385-4.058q.429-.324.969-.324t.97.324m.8 8.811q.73-.73.73-1.769t-.73-1.77T12 9.5t-1.77.73T9.5 12t.73 1.77t1.77.73t1.77-.73m-2.829-.711Q10.5 12.617 10.5 12t.441-1.059T12 10.5t1.059.441q.441.442.441 1.059t-.441 1.059T12 13.5t-1.059-.441m1.001 4.441q-1.275 0-2.48.385q-1.206.384-2.273 1.115h9.527q-1.049-.73-2.264-1.115t-2.51-.385M6 10.308v8.384q1.262-1.051 2.777-1.622q1.515-.57 3.165-.57q1.67 0 3.224.56q1.553.561 2.834 1.613v-8.365q0-.154-.067-.28t-.183-.22l-5.384-4.039q-.154-.134-.366-.134t-.365.134L6.25 9.808q-.115.096-.183.22t-.067.28M12 12");
}

</style>
