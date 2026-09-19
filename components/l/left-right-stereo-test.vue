<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e91hltl8u"/><path class="n84g8qbqq"/><path class="bmh5b5bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:left-right-stereo-test" /></template>
<style>
.bmh5b5bta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.707 31.856c2.58-13.65 7.237-24.867-1.673-27.255c-2.535-.676-5.487 2.11-6.594 6.222s.051 7.995 2.586 8.671a5.04 5.04 0 0 0 4.455-1.046s-2.546 12.67-2.137 12.99a2.7 2.7 0 0 0 3.363.418M20.863 16.293a9.32 9.32 0 0 0-.866-10.06m6.669 10.251s-2.988-3.983.604-9.714");
}

.e91hltl8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.198 32.168a10.84 10.84 0 0 0 .442 5.72c1.1 3.041 4.254 4.695 4.352 5.612");
}

.n84g8qbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.293 31.856C7.713 18.206 3.056 6.989 11.966 4.6c2.535-.676 5.487 2.11 6.594 6.222s-.051 7.995-2.586 8.671a5.04 5.04 0 0 1-4.455-1.046s2.546 12.67 2.137 12.99a2.7 2.7 0 0 1-3.363.418Zm25.509.312a10.84 10.84 0 0 1-.442 5.72c-1.1 3.041-1.964 4.695-2.062 5.612");
}

</style>
