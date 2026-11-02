<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzbz7fr0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzbz7fr0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-big-line" /></template>
