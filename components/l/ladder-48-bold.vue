<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klcw8eg5x.css';
import '../../css/n/nbve-mbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="klcw8eg5x"/><path class="nbve-mbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladder-48-bold" /></template>
