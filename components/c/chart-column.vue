<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d19_u-5hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d19_u-5hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-column" /></template>
