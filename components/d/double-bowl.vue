<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlav2wb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:double-bowl" /></template>
<style>
.wlav2wb4a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.756 8.906q-.019.147.02.29l1.293 4.74q-1.319.497-1.319 2.313q0 1.036.732 1.768t1.768.732h15.5q1.036 0 1.768-.732t.732-1.768q0-1.816-1.319-2.313l1.293-4.74Q22.25 9.1 22.25 9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-8q-.1 0-.197.026q-.072.02-.138.053t-.124.078t-.107.101t-.085.12t-.06.134t-.033.143t-.004.147t.024.145l1.242 4.553H9.982l1.241-4.552l.001-.001l.002-.01q.024-.092.024-.187v-.009q-.001-.042-.006-.084Q10.787 5.25 6.5 5.25T1.756 8.906m1.712-.656q.661-1.5 3.032-1.5t3.032 1.5zm.014 1.5h6.036l-1.091 4H4.573z");
}

</style>
