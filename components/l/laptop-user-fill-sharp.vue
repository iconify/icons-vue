<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0t4x6kjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-user-fill-sharp" /></template>
<style>
.x0t4x6kjb {
  fill: currentColor;
  d: path("M4 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v11h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1Zm6.832 1.236a3 3 0 1 0 2.338 5.527a3 3 0 0 0-2.338-5.527M15 15a1 1 0 0 0 1-1c0-.257-.075-.506-.209-.725C15.124 12.188 13.099 12 12 12s-3.124.188-3.791 1.275A1.4 1.4 0 0 0 8 14a1 1 0 0 0 1 1Zm5 2H4v2h16Z");
}

</style>
