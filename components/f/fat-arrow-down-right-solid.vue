<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4qxexjsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4qxexjsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-down-right-solid" /></template>
