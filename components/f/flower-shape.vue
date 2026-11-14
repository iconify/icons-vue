<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfsumbf1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flower-shape" /></template>
<style>
.jfsumbf1u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.879 4.85q-.866-.237-1.842-.071q-1.957.333-2.958 2.048q-1 1.716-.327 3.583q.342.948.99 1.59q-.648.642-.99 1.59q-.673 1.867.327 3.583q1.001 1.715 2.958 2.048q.976.166 1.842-.071q.233.86.865 1.613q1.274 1.518 3.256 1.518t3.256-1.518q.632-.753.865-1.613q.866.237 1.842.071q1.957-.333 2.958-2.048q1-1.716.327-3.583q-.342-.948-.99-1.59q.648-.642.99-1.59q.673-1.867-.327-3.583q-1.001-1.715-2.958-2.048q-.976-.166-1.842.071q-.233-.86-.865-1.613Q13.982 1.719 12 1.719T8.744 3.237q-.632.753-.865 1.613M12 9.75q2.25 0 2.25 2.25T12 14.25T9.75 12T12 9.75m0 3q-.75 0-.75-.75t.75-.75t.75.75t-.75.75");
}

</style>
