<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qibsfwb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-cerium" /></template>
<style>
.qibsfwb6b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25m10.512 10.072q1.428-2.24.524-3.926q-.912-1.702-3.545-1.661q-2.368.036-4.916 1.476q-2.545 1.438-3.837 3.467q-1.428 2.24-.524 3.926q.912 1.702 3.545 1.661q2.368-.036 4.916-1.476q2.545-1.438 3.837-3.467");
}

</style>
