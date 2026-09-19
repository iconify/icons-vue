<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8fs50_cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8fs50_cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chart-pie" /></template>
