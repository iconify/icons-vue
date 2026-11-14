<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf08u3bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arc-flash" /></template>
<style>
.gf08u3bdu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.25q2.5 0 2.5 2.5v4l1.65-2.2q.09-.119.218-.195t.276-.097t.292.015t.264.127q.098.074.168.175q.069.101.103.219l1.47 5.146l2.138-4.275q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.109.055.195.141l1.72 1.719V5.75q0-1.036.732-1.768t1.768-.732t1.768.732t.732 1.768v12.5q0 1.036-.732 1.768t-1.768.732t-1.768-.732t-.732-1.768v-5.939l-2.045-2.045l-2.534 5.069q-.071.141-.192.242t-.273.144q-.143.041-.292.024q-.148-.017-.278-.089q-.131-.073-.223-.19q-.093-.117-.134-.26L9.194 9.658L7.25 12.25v6q0 2.5-2.5 2.5t-2.5-2.5V5.75q0-2.5 2.5-2.5");
}

</style>
