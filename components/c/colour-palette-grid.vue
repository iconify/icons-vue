<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbgzdgbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-palette-grid" /></template>
<style>
.bbgzdgbig {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.25h-2.25q-1.398 0-2.386.989q-.989.988-.989 2.386v2.25q0 1.398.989 2.386q.988.989 2.386.989h2.25q3.375 0 3.375-3.375v-2.25q0-1.398-.989-2.386q-.988-.989-2.386-.989m8.25 0h2.25q1.398 0 2.386.989q.989.988.989 2.386v2.25q0 3.375-3.375 3.375h-2.25q-3.375 0-3.375-3.375v-2.25q0-1.398.989-2.386q.988-.989 2.386-.989m-8.25 10.5h-2.25q-1.398 0-2.386.989q-.989.988-.989 2.386v2.25q0 1.398.989 2.386q.988.989 2.386.989h2.25q3.375 0 3.375-3.375v-2.25q0-3.375-3.375-3.375m9.961.281q.357.448.999 1.231q2.415 2.945 2.415 4.238q0 4-4 4t-4-4q0-1.293 2.415-4.238q.642-.784.999-1.231q.046-.057.103-.105t.121-.083t.135-.058t.144-.03q.074-.009.147-.002q.074.006.145.027t.136.054t.124.08q.065.052.117.117");
}

</style>
