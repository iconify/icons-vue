<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi44eeo5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bedtime-rounded" /></template>
<style>
.hi44eeo5p {
  fill: currentColor;
  d: path("M12.1 21q-1.888 0-3.543-.713t-2.892-1.951t-1.951-2.893T3 11.9q0-2.565 1.32-4.733t3.613-3.313q.396-.2.765.003q.37.203.402.624q.137 2.048.954 3.906q.817 1.857 2.26 3.3t3.28 2.25t3.887.944q.457.033.664.409t.007.777q-1.158 2.289-3.322 3.611T12.1 21");
}

</style>
