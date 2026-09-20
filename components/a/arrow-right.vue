<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qok_cu2qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qok_cu2qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-right" /></template>
