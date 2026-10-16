<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mby54wt2i.css';
import '../../css/p/p-azqib5q.css';
import '../../css/m/mn7eeg1uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mby54wt2i"/><path class="p-azqib5q"/><path class="mn7eeg1uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:greenhouse-20" /></template>
