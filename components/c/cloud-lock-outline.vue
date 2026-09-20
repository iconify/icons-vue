<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvvr0wqdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cloud-lock-outline" /></template>
<style>
.hvvr0wqdy {
  fill: currentColor;
  d: path("M13.404 19H6.5q-1.871 0-3.185-1.306Q2 16.39 2 14.517q0-1.776 1.223-3.08t2.873-1.402q.337-2.185 2.01-3.61T12 5q2.15 0 3.757 1.318t2.072 3.317q-.256.019-.494.074q-.237.054-.476.139q-.373-1.644-1.73-2.746Q13.77 6 12 6Q9.925 6 8.463 7.463T7 11h-.538q-1.393 0-2.427 1.025T3 14.5t1.025 2.475T6.5 18h6.904zm3.192 0q-.348 0-.578-.23t-.23-.578v-2.711q0-.348.269-.568t.635-.22v-1q0-.71.501-1.211t1.21-.501t1.202.5t.491 1.211v1q.367 0 .636.22t.268.569v2.711q0 .349-.23.578t-.578.23zm.866-4.308h1.865v-1q0-.425-.249-.683q-.25-.259-.674-.259t-.684.259q-.258.258-.258.683z");
}

</style>
