<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1s_q4o7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-bolt-rounded" /></template>
<style>
.a1s_q4o7x {
  fill: currentColor;
  d: path("M4.385 17q-1 0-1.693-.692T2 14.616V9.385q0-1 .692-1.693T4.385 7h12.167q.362 0 .518.322t-.07.592l-4.504 5.615q-.323.404-.108.86t.73.457h3.113l-.285 1.425q-.055.312-.254.52q-.198.209-.548.209zm13.861-.675q-.105.13-.255.066q-.149-.066-.118-.227l.598-3.318h-2.017q-.268 0-.367-.217t.063-.429l3.604-4.525q.105-.13.255-.066q.149.066.118.227l-.598 3.318h2.017q.268 0 .367.217t-.063.429z");
}

</style>
