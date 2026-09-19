<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o28emeehs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o28emeehs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-chart-column" /></template>
