<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-8637bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drone-view" /></template>
<style>
.i-8637bwo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1.75Q1.75 1.75 1.75 4T4 6.25q.595 0 1.032-.157L8.47 9.53q.086.087.196.141q-.416.769-.416 1.954v.75q0 1.185.416 1.954q-.11.054-.196.141l-3.438 3.437Q4.595 17.75 4 17.75q-2.25 0-2.25 2.25T4 22.25T6.25 20q0-.595-.157-1.032L9.53 15.53q.087-.086.141-.196q.769.416 1.954.416h.75q1.185 0 1.954-.416q.054.11.141.196l3.437 3.438q-.157.437-.157 1.032q0 2.25 2.25 2.25T22.25 20T20 17.75q-.595 0-1.032.157L15.53 14.47q-.086-.087-.196-.141q.416-.769.416-1.954v-.75q0-1.185-.416-1.954q.11-.054.196-.141l3.438-3.437q.437.157 1.032.157q2.25 0 2.25-2.25T20 1.75T17.75 4q0 .595.157 1.032L14.47 8.47q-.087.086-.141.196q-.769-.416-1.954-.416h-.75q-1.185 0-1.954.416q-.054-.11-.141-.196L6.093 5.032Q6.25 4.595 6.25 4q0-2.25-2.25-2.25");
}

</style>
