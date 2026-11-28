<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy-7kibrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy-7kibrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bar-chart" /></template>
