<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngkdydb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ngkdydb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:cloudy-windy" /></template>
