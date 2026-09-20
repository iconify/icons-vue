<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaa3sk3ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-button-r1-sharp" /></template>
<style>
.kaa3sk3ya {
  fill: currentColor;
  d: path("M22 4v12q0 1.65-1.175 2.825T18 20H6q-1.65 0-2.825-1.175T2 16V4zm-6.7 11.5h1.375v-7h-.925l-2.475 1.8l.725.975l1.3-.975zm-7.975 0H8.7v-2.55h.9l1.825 2.55h1.625l-2.025-2.725q.7-.275 1.063-.787t.362-1.263q0-1.125-.662-1.675T9.775 8.5h-2.45zM8.7 11.925V9.7h1.125q.65 0 .938.288t.287.812q0 .55-.337.838t-.913.287z");
}

</style>
