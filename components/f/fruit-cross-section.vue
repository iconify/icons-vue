<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffgnyup_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fruit-cross-section" /></template>
<style>
.ffgnyup_g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.355 3.632q1.971-.476 4.139.496Q21.25 5.812 21.25 11q0 4.697-2.736 7.98q-2.725 3.27-6.514 3.27t-6.514-3.27Q2.75 15.697 2.75 11q0-5.188 3.756-6.872q2.705-1.213 5.104-.172l.694-1.735q.027-.068.067-.13t.092-.115t.113-.094q.061-.042.129-.071q.067-.029.14-.045q.072-.015.146-.016t.146.013q.073.013.142.041q.138.055.245.159t.165.242t.061.286t-.054.288zM10 9.75q0 2.75 2 2.75t2-2.75T12 7t-2 2.75M8.75 12.5q-2 0-2 2.75t2 2.75t2-2.75t-2-2.75m4.5 2.75q0 2.75 2 2.75t2-2.75t-2-2.75t-2 2.75");
}

</style>
