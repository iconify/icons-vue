<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kot2fy1te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kot2fy1te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:flower-2-solid" /></template>
