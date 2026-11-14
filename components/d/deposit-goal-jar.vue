<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsodjvbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deposit-goal-jar" /></template>
<style>
.qsodjvbou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 4.75V2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q.094 0 .186.023q.091.024.174.069t.151.109q.069.065.12.144q.377-.066.786.062l.807.252q.985.309.985 1.341t-.985 1.341l-.51.159h.036q2 0 2 2q0 .736-.271 1.201Q19.75 9.99 19.75 12.5V19q0 3.25-3.25 3.25h-9q-1.346 0-2.298-.952T4.25 19v-6.5q0-2.51 1.771-4.549q-.271-.465-.271-1.201q0-2 2-2zm-4.5 8q0 1.094.436 1.753q-.092-.003-.186-.003q-2.75 0-2.75 2.75T9.5 20q1.921 0 2.5-1.342Q12.579 20 14.5 20q2.75 0 2.75-2.75T14.5 14.5q-.094 0-.186.003q.436-.659.436-1.753Q14.75 10 12 10t-2.75 2.75m2.564 2.747q.106.159.186.345q.08-.186.186-.345q-.092.003-.186.003t-.186-.003");
}

</style>
