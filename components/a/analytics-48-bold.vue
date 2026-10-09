<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz0-7c0kb.css';
import '../../css/f/fpw9y5b6x.css';
import '../../css/h/hjih05f-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oz0-7c0kb"/><path class="fpw9y5b6x"/><path class="hjih05f-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:analytics-48-bold" /></template>
