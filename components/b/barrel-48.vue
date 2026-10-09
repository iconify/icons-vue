<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh0wmoblc.css';
import '../../css/o/oxbk-rb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qh0wmoblc"/><path class="oxbk-rb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barrel-48" /></template>
