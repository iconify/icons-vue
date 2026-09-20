<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pna-dobsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pna-dobsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:line-chart-square-solid" /></template>
