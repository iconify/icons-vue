<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it7-fkk5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it7-fkk5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:line-chart-square-filled" /></template>
