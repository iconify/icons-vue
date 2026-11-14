<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5y99-g9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:button-icon" /></template>
<style>
.r5y99-g9k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 2.25h-4q-3.21 0-5.48 2.27T2.25 10v4q0 3.21 2.27 5.48T10 21.75h4q3.21 0 5.48-2.27T21.75 14v-4q0-3.21-2.27-5.48T14 2.25m-.574 5.947l.382.905q.176.417.627.456l.979.084q1.022.089 1.338 1.064q.317.974-.456 1.646l-.744.645q-.341.296-.239.737l.223.958q.231.999-.598 1.602q-.83.603-1.709.074l-.842-.509q-.387-.234-.774 0l-.841.508q-.88.53-1.71-.073q-.829-.603-.598-1.603l.222-.956q.103-.442-.238-.738l-.743-.644q-.774-.673-.457-1.647q.316-.975 1.336-1.064l.981-.084q.451-.039.627-.456l.382-.905q.4-.945 1.426-.945t1.426.945");
}

</style>
