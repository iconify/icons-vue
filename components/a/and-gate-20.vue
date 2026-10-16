<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih1_q1b8g.css';
import '../../css/m/mllvz95kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ih1_q1b8g"/><path class="mllvz95kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:and-gate-20" /></template>
