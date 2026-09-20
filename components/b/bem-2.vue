<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":220};
const content = `<path class="e51ee2brh"/><path class="m-6f0h3lf"/><path class="tab16nb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bem-2" /></template>
<style>
.e51ee2brh {
  fill: var(--svg-color--010101, #010101);
  d: path("M146.335 187.82h108.833v31.347H146.335z");
}

.m-6f0h3lf {
  fill: var(--svg-color--f7b334, #f7b334);
  d: path("M130.075 187.82v-56.947H78.937v56.947z");
}

.tab16nb5n {
  fill: var(--svg-color--010101, #010101);
  d: path("M108.047 62.171h-41.96L34.092 0H.262v187.82H79.2v-56.947h66.874V100.05c0-21.42-15.473-37.878-38.026-37.878m12.587 50.94h-11.538l-13.113-2.874v-2.874h24.651z");
}

</style>
