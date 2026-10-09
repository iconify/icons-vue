<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-h4xkbtz.css';
import '../../css/p/p1ofzbbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-h4xkbtz"/><path class="p1ofzbbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jersey-20" /></template>
