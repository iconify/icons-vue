<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5ebr9bjc.css';
import '../../css/n/ng0ti4b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5ebr9bjc"/><path class="ng0ti4b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fast-48" /></template>
