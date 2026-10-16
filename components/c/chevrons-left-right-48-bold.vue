<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omvg85bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omvg85bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-right-48-bold" /></template>
