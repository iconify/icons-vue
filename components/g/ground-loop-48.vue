<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4gy22yti.css';
import '../../css/i/ifweg2bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4gy22yti"/><path class="ifweg2bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-loop-48" /></template>
