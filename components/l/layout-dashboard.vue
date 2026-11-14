<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuw752bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-dashboard" /></template>
<style>
.wuw752bif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.371 3.129Q6.493 2.25 5.25 2.25t-2.121.879q-.879.878-.879 2.121v13.5q0 1.243.879 2.121q.878.879 2.121.879q3 0 3-3V5.25q0-1.243-.879-2.121m5.754-.879h5.25q1.398 0 2.386.989q.989.988.989 2.386v2.75q0 1.398-.989 2.386q-.988.989-2.386.989h-5.25q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-2.75q0-1.398.989-2.386q.988-.989 2.386-.989m1.106 11.769q-.769-.769-1.856-.769q-2.625 0-2.625 2.625v3.25q0 1.087.769 1.856t1.856.769t1.856-.769t.769-1.856v-3.25q0-1.087-.769-1.856m4.894-.769q1.087 0 1.856.769t.769 1.856v3.25q0 1.087-.769 1.856t-1.856.769q-2.625 0-2.625-2.625v-3.25q0-2.625 2.625-2.625");
}

</style>
