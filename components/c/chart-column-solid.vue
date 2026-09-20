<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu6_zjylq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu6_zjylq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-column-solid" /></template>
