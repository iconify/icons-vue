<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl67psbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-post-office-outline" /></template>
<style>
.zl67psbxm {
  fill: currentColor;
  d: path("M16 19v2q0 .425-.288.713T15 22H3q-.425 0-.712-.288T2 21v-8q0-.425.288-.712T3 12h3V8q0-2.5 1.75-4.25T12 2h4q2.5 0 4.25 1.75T22 8v14h-2v-3zm0-2h4V8q0-1.65-1.175-2.825T16 4h-4q-1.65 0-2.825 1.175T8 8v4h7q.425 0 .713.288T16 13zm-6-7V8h8v2zm-1 6.85L14 14H4zm0 1.75l-5-2.85V20h10v-4.25zM4 14v6z");
}

</style>
