<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oss575b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-post-office-outline-rounded" /></template>
<style>
.oss575b3j {
  fill: currentColor;
  d: path("M3.77 21q-.31 0-.54-.23T3 20.23v-6.46q0-.31.23-.54t.54-.23H7V8q0-2.077 1.462-3.538T12 3h4q2.077 0 3.539 1.462T21 8v12.5q0 .214-.143.357T20.5 21t-.357-.143T20 20.5V18h-5v2.23q0 .31-.23.54t-.54.23zM15 17h5V8q0-1.65-1.175-2.825T16 4h-4q-1.65 0-2.825 1.175T8 8v5h6.23q.31 0 .54.23t.23.54zm-6.308-.323q.154.096.308.096t.308-.096L14 14H4zM4 20h10v-4.98l-4.192 2.39q-.187.106-.389.161T9 17.627t-.42-.056t-.388-.161L4 15.02zm0-6v.38v-.014v.782v-.129V20v-4.98v.128v-.783v.016zm7-4.5q-.213 0-.357-.143T10.5 9t.143-.357T11 8.5h6q.214 0 .357.143T17.5 9t-.143.357T17 9.5z");
}

</style>
