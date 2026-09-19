<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7lwqcc9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7lwqcc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-donut-filled" /></template>
