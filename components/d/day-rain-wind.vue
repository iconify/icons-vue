<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qamee38ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="qamee38ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:day-rain-wind" /></template>
