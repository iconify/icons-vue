<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkdjfdcyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="mkdjfdcyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:arrow-down-left" /></template>
