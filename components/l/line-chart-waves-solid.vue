<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgnbkldne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnbkldne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:line-chart-waves-solid" /></template>
