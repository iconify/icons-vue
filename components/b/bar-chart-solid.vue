<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3jsx340p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3jsx340p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bar-chart-solid" /></template>
