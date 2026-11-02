<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r27q04b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r27q04b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-2-fill" /></template>
