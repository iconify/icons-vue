<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yavy7abjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:courier-person" /></template>
<style>
.yavy7abjh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.141 3.641Q5.75 5.032 5.75 7t1.391 3.359T10.5 11.75t3.359-1.391T15.25 7t-1.391-3.359T10.5 2.25T7.141 3.641M2.25 19.5q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673q2.276 0 4.059.723Q13 14.832 13 17.25v2.5q0 .812.3 1.5H4q-1.75 0-1.75-1.75m14.5-4.75h3q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-3q-1.036 0-1.768-.732t-.732-1.768v-2.5q0-2.5 2.5-2.5m0 1.5q-1 0-1 1v2.5q0 .414.293.707t.707.293h3q.414 0 .707-.293t.293-.707v-2.5q0-1-1-1zM17 17.5h2v1q0 .165-.069.315q-.07.15-.196.257q.015.211.015.428H17z");
}

</style>
