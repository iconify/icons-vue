<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu2h69dkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bus-map-pin-2-sharp" /></template>
<style>
.lu2h69dkq {
  fill: currentColor;
  d: path("M5.616 21v-1.616H4V5.81h1.616V4h7.875q-.049.216-.069.434t-.031.45H6.616v1.943h7.19q.08.244.188.485q.108.24.268.515H5.019v4.25h13.139l.842.721l1-.834v7.42h-1.616V21h-1.942v-1.616H7.54V21zM18.422 5.401q-.23-.233-.23-.578t.234-.574t.577-.23t.575.233t.23.578t-.233.575t-.578.23t-.575-.234M19 9.673q1.621-1.379 2.426-2.572t.805-2.2q0-1.37-.932-2.338T19 1.596t-2.299.967t-.932 2.337q0 1.008.805 2.201T19 9.673M6.827 16.231h2.865v-1H6.827zm7.5 0h2.865v-1h-2.865z");
}

</style>
