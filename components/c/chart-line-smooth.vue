<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjwtpxbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjwtpxbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-line-smooth" /></template>
