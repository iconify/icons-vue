<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3tya0m_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:door-knob" /></template>
<style>
.m3tya0m_h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 4.75q2.75 0 2.75 2.75v2.25h1.864q.485-1.395 1.613-2.523Q12.704 5.25 15.5 5.25t4.773 1.977T22.25 12t-1.977 4.773T15.5 18.75t-4.773-1.977q-1.128-1.128-1.613-2.523H7.25v2.25q0 2.75-2.75 2.75T1.75 16.5v-9q0-1.139.805-1.945q.806-.805 1.945-.805m2.75 6.5v1.5h1.537q-.037-.367-.037-.75t.037-.75z");
}

</style>
