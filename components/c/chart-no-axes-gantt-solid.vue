<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo2rccr6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo2rccr6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-gantt-solid" /></template>
