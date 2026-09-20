<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af6jmvr1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbud-right-outline-rounded" /></template>
<style>
.af6jmvr1s {
  fill: currentColor;
  d: path("M12.442 11.673h-2.75v-1h2.943q.343 0 .575.232q.232.233.232.576v7.904q0 .269.174.442q.173.173.442.173h1.538q.27 0 .443-.173t.173-.442V11.48q0-.343.232-.576t.575-.232h1.366q.269 0 .442-.173t.173-.442V6.616q0-.27-.173-.443T18.384 6H9.692V5h8.693q.69 0 1.153.463T20 6.616v3.442q0 .69-.462 1.153t-1.153.462h-1.173v7.712q0 .69-.463 1.152T15.596 21h-1.538q-.69 0-1.153-.462t-.463-1.153zM5.423 4.577Q6.846 3 8.961 3q.311 0 .521.21t.21.52v9.212q0 .311-.21.521t-.52.21q-2.116 0-3.539-1.586T4 8.327t1.423-3.75m.604 6.729q1.027 1.277 2.665 1.377V3.99q-1.638.08-2.665 1.357T5 8.327t1.027 2.979m2.665-2.979");
}

</style>
