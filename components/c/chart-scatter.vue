<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx6aa2bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx6aa2bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-scatter" /></template>
