<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpoubbo_e.css';
import '../../css/a/aydz6gbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="aydz6gbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:line-chart-square" /></template>
