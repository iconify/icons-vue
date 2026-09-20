<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so6g50bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so6g50bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drive-line" /></template>
