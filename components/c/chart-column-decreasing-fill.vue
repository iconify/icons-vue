<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqrr3e9vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrr3e9vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-decreasing-fill" /></template>
