<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogm4z_b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-lock" /></template>
<style>
.ogm4z_b0d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.5q0-1.139.805-1.945Q3.861 5.75 5 5.75h2.075l1.282-2.136q.05-.083.119-.151q.07-.068.154-.116q.085-.048.179-.072q.094-.025.191-.025h6q.097 0 .191.025q.094.024.179.072t.154.116t.119.151l1.282 2.136H19q2.75 0 2.75 2.75V18q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75zm9 3h1.5V11q0-.75-.75-.75t-.75.75zm3 .214V11q0-2.25-2.25-2.25T9.75 11v.714Q8.5 12.232 8.5 14v1q0 1.036.732 1.768T11 17.5h2q1.036 0 1.768-.732T15.5 15v-1q0-1.768-1.25-2.286");
}

</style>
