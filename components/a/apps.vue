<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcgr42bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:apps" /></template>
<style>
.jcgr42bhq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7q0-1.76 1.245-3.005T17 2.75t3.005 1.245T21.25 7t-1.245 3.005T17 11.25t-3.005-1.245T12.75 7m-2.745-3.005Q8.76 2.75 7 2.75T3.995 3.995T2.75 7t1.245 3.005T7 11.25t3.005-1.245T11.25 7t-1.245-3.005m0 10Q8.76 12.75 7 12.75t-3.005 1.245T2.75 17t1.245 3.005T7 21.25t3.005-1.245T11.25 17t-1.245-3.005M17 12.75q1.76 0 3.005 1.245T21.25 17t-1.245 3.005T17 21.25t-3.005-1.245T12.75 17t1.245-3.005T17 12.75");
}

</style>
