<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my9xahb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my9xahb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-column-decreasing" /></template>
