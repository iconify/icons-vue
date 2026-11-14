<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or0duqbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-date-24-regular" /></template>
<style>
.or0duqbis {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM4.5 17.75c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V8.5h-15zm4.662-6.966a.75.75 0 0 1 1.338.466V17A.75.75 0 0 1 9 17v-3.977a9 9 0 0 1-.85.61a.75.75 0 0 1-.8-1.267a8 8 0 0 0 1.699-1.448l.089-.104l.02-.025zm5.338-.534c1.18 0 2.25.891 2.25 2.125c0 .512-.187.963-.486 1.317c.45.423.736 1.01.736 1.683c0 1.363-1.173 2.375-2.5 2.375S12 16.738 12 15.375c0-.673.286-1.26.735-1.683a2.02 2.02 0 0 1-.485-1.317c0-1.234 1.07-2.125 2.25-2.125m0 4.25c-.606 0-1 .443-1 .875s.394.875 1 .875s1-.443 1-.875s-.394-.875-1-.875m0-2.75c-.477 0-.75.34-.75.625s.273.625.75.625s.75-.34.75-.625s-.273-.625-.75-.625M6.25 4.5A1.75 1.75 0 0 0 4.5 6.25V7h15v-.75a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
