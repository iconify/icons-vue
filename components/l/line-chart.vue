<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzk2onifa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzk2onifa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:line-chart" /></template>
