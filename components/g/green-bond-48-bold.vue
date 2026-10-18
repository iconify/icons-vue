<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1y5cbbe.css';
import '../../css/j/j8h-reucj.css';
import '../../css/d/dit17kuus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jj1y5cbbe"/><path class="j8h-reucj"/><path class="dit17kuus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-bond-48-bold" /></template>
