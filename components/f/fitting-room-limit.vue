<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0_hn7bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fitting-room-limit" /></template>
<style>
.q0_hn7bzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5v-1a2 2 0 1 0-2-2m3.448 9h-5.33q-.131 0-.261-.021q-.129-.021-.254-.063q-.124-.042-.24-.103t-.221-.14T6.946 13q-.091-.095-.165-.203t-.131-.226t-.092-.245q-.037-.126-.053-.256q-.015-.131-.01-.262t.031-.259q.027-.129.073-.252q.047-.122.112-.236q.066-.114.149-.215q.083-.102.181-.189t.209-.157l3.348-2.115q.157-.099.325-.175q.169-.076.347-.127t.361-.078t.369-.026t.369.026t.361.078q.178.051.347.127t.325.175L16.75 10.5q.13.082.243.188q.112.105.203.23q.09.124.156.264q.065.139.104.288M15.5 15.75c.25-1 1.25-1.5 2.5-1.5c1.5 0 2.5.75 2.5 2c0 1-1 1.5-2.25 1.5c1.5 0 2.5.75 2.5 2s-1.25 2-2.75 2c-1.25 0-2.25-.5-2.75-1.5");
}

</style>
