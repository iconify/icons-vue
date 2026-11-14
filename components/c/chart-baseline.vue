<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqwsscchg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-baseline" /></template>
<style>
.sqwsscchg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.813 3.125q-2.508 0-4.971 4.516q-.036.065-.058.135t-.03.144t-.001.147t.027.145q.021.07.056.136q.034.065.08.123q.047.057.103.105q.057.047.122.082q.131.072.279.088t.292-.026t.259-.136t.187-.225q2.037-3.734 3.655-3.734q1.489 0 2.463 3.572q.203.743.516 2.053H3.5q-1.75 0-1.75 1.75t1.75 1.75h7.127q2.191 8.5 4.873 8.5q2.212 0 4.496-4.08q1.227-2.193 1.839-2.499q.134-.067.232-.18q.097-.112.145-.254q.047-.141.036-.29q-.01-.149-.077-.282q-.033-.066-.079-.125q-.045-.058-.101-.107q-.055-.048-.12-.085q-.064-.036-.134-.06q-.07-.023-.143-.032t-.147-.004t-.145.025t-.137.052q-1.025.513-2.478 3.108q-1.855 3.313-3.187 3.313q-1.535 0-3.331-7H20.5q1.75 0 1.75-1.75t-1.75-1.75h-9.166q-.376-1.587-.61-2.447q-1.276-4.678-3.911-4.678");
}

</style>
