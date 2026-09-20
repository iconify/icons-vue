<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg0_p6zxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg0_p6zxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bar-chart-horizontal" /></template>
