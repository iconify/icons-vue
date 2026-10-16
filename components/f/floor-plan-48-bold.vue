<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3k4bybje.css';
import '../../css/e/eo7syfsuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g3k4bybje"/><path class="eo7syfsuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floor-plan-48-bold" /></template>
