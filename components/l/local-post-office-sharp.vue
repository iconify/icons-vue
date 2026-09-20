<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5n3u070i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-post-office-sharp" /></template>
<style>
.j5n3u070i {
  fill: currentColor;
  d: path("M2 22V12h4V8q0-2.5 1.75-4.25T12 2h4q2.5 0 4.25 1.75T22 8v14h-2v-3h-4v3zm7-5.15L4 14v1.75l5 2.85l5-2.85V14zm7 .15h4V8q0-1.65-1.175-2.825T16 4h-4q-1.65 0-2.825 1.175T8 8v4h8zm-6-7V8h8v2z");
}

</style>
