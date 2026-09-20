<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpo-87w4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="kpo-87w4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:link-off" /></template>
