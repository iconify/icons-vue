<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjsj_ebfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjsj_ebfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-gantt-fill" /></template>
