<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hun5gnd_j.css';
import '../../css/j/jh9opkozm.css';
import '../../css/j/j5lerzb3y.css';
import '../../css/s/skly4o5tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hun5gnd_j"/><path class="jh9opkozm"/><path class="j5lerzb3y"/><path class="skly4o5tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-treemap-48" /></template>
