<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omcfeqiag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brush-outline" /></template>
<style>
.omcfeqiag {
  fill: currentColor;
  d: path("M6 21q-1.125 0-2.225-.55T2 19q.65 0 1.325-.513T4 17q0-1.25.875-2.125T7 14t2.125.875T10 17q0 1.65-1.175 2.825T6 21m0-2q.825 0 1.412-.587T8 17q0-.425-.288-.712T7 16t-.712.288T6 17q0 .575-.137 1.05t-.363.9q.125.05.25.05zm5.75-4L9 12.25l8.95-8.95q.275-.275.688-.288t.712.288l1.35 1.35q.3.3.3.7t-.3.7zM7 17");
}

</style>
