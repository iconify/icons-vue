<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_m9rwwaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kendo-tare" /></template>
<style>
.q_m9rwwaj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 3.25H4.25q-1.036 0-1.768.732T1.75 5.75t.732 1.768q.549.548 1.268.686V14q0 2.75 2.75 2.75h1.25v1.75q0 2.75 2.75 2.75h3q2.75 0 2.75-2.75v-1.75h1.25q2.75 0 2.75-2.75V8.204q.719-.138 1.268-.686q.732-.732.732-1.768t-.732-1.768t-1.768-.732m-12 12H6.5q-1.25 0-1.25-1.25V8.25h2.5zm1.5-7h5.5V18.5q0 1.25-1.25 1.25h-3q-1.25 0-1.25-1.25zm8.25 7h-1.25v-7h2.5V14q0 1.25-1.25 1.25");
}

</style>
