<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogic63blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:forum-expert" /></template>
<style>
.ogic63blb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.625 5.098Q16.005 2.75 12 2.75T5.375 5.098Q2.75 7.449 2.75 11q0 2.887 1.409 4.879L2.793 19.75q-.046.129-.043.265q.003.137.054.264q.055.138.159.245t.242.165q.137.059.286.061t.288-.054l4.776-1.91q1.944.464 3.445.464q4.005 0 6.625-2.348Q21.25 14.551 21.25 11t-2.625-5.902m-5.384 2.823l.207.456q.176.388.6.436l.495.055q.875.096 1.147.934q.272.837-.38 1.429l-.368.336q-.314.286-.228.704l.1.491q.176.86-.534 1.376q-.711.515-1.474.082l-.435-.247q-.371-.21-.742 0l-.435.247q-.763.433-1.474-.082q-.71-.516-.534-1.376l.1-.49q.086-.419-.229-.706l-.368-.335q-.651-.592-.379-1.429t1.147-.934l.497-.055q.422-.048.598-.436l.207-.456q.364-.799 1.241-.799t1.241.798z");
}

</style>
