<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qent2vxee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:double-trailer" /></template>
<style>
.qent2vxee {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 4.75h2q2.5 0 2.5 2.5v5H10v-5q0-2.5 2.5-2.5h2q1.036 0 1.768.732T17 7.25h2q.167 0 .318.071t.258.199l2.5 3q.084.101.129.225q.045.123.045.255v4q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.127q.127.436.127 1q0 2.5-2.5 2.5t-2.5-2.5q0-.564.127-1h-.377q-.228 0-.418-.127q.168.48.168 1.127q0 2.5-2.5 2.5t-2.5-2.5q0-.789.249-1.329q-.275-.161-.517-.403q-.548-.549-.686-1.268H8.704q-.138.719-.686 1.268q-.242.242-.517.403q.249.54.249 1.329q0 2.5-2.5 2.5t-2.5-2.5q0-.789.249-1.329q-.275-.161-.517-.403q-.732-.732-.732-1.768v-6q0-2.5 2.5-2.5M19 14.25h1.75v-2.978L18.649 8.75H17v4.5q0 .541-.2 1z");
}

</style>
