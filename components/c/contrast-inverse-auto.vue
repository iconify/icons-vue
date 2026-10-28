<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia1jw012t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contrast-inverse-auto" /></template>
<style>
.ia1jw012t {
  fill: currentColor;
  d: path("M3 12q0-1.767.643-3.333q.644-1.565 1.753-2.77q1.11-1.207 2.618-1.965t3.236-.893h.023q-.206.257-.36.526q-.154.268-.294.56q-2.786.5-4.703 2.68Q4 8.988 4 12q0 3.267 2.186 5.505t5.314 2.478v-6.598h9.392q-.232 1.611-1.027 2.999q-.796 1.387-1.976 2.417t-2.685 1.615T12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12m10.377-1l3.47-9h.73l3.508 9H20.03l-1.008-2.539H15.4L14.392 11zm2.32-3.35h3.03l-1.496-3.996h-.077z");
}

</style>
