<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnjcr8b9t.css';
import '../../css/v/v8g6tabng.css';
import '../../css/j/jjjiu_baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnjcr8b9t"/><path class="v8g6tabng"/><path class="jjjiu_baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circuit-breaker-48-bold" /></template>
