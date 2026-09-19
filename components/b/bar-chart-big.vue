<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdyb6n7ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdyb6n7ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bar-chart-big" /></template>
