<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eug_biruv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="eug_biruv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:delete-1" /></template>
