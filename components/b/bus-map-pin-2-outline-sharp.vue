<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxfrikbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bus-map-pin-2-outline-sharp" /></template>
<style>
.bxfrikbla {
  fill: currentColor;
  d: path("M5.616 21v-1.616H4V5.81h1.616V4h7.875q-.049.216-.069.434t-.031.45H6.616v1.943h7.19q.08.244.188.485q.108.24.268.515H5.019v4.25h13.139l.842.721l1-.834v7.42h-1.616V21h-1.942v-1.616H7.54V21zM18.422 5.401q-.23-.233-.23-.578t.234-.574t.577-.23t.575.233t.23.578t-.233.575t-.578.23t-.575-.234m2.237-2.21q.687.711.687 1.713q0 .746-.579 1.631q-.58.885-1.761 1.965q-1.179-1.085-1.766-1.967q-.586-.882-.586-1.625q0-.999.686-1.713q.687-.714 1.66-.714t1.66.71M19 9.674q1.621-1.379 2.426-2.572t.805-2.2q0-1.37-.932-2.338T19 1.596t-2.299.967t-.932 2.337q0 1.008.805 2.201T19 9.673M5.02 13.077v5.308h14v-5.308zm1.807 3.154h2.865v-1H6.827zm7.5 0h2.865v-1h-2.865zm-9.308 2.153v-5.307z");
}

</style>
