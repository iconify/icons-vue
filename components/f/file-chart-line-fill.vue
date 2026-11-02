<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayk_p8mde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayk_p8mde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-chart-line-fill" /></template>
