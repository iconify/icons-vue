<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyhgvun_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyhgvun_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-chart-line" /></template>
