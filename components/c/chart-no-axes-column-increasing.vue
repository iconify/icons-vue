<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgadrsbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgadrsbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-column-increasing" /></template>
