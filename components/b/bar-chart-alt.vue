<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmc-b_jyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmc-b_jyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-chart-alt" /></template>
