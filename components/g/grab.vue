<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeq1y5_1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qeq1y5_1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grab" /></template>
