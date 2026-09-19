<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpfzbnbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpfzbnbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:doughnut-chart" /></template>
