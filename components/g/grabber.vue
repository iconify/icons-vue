<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo6ln3mqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":16};
const content = `<path class="vo6ln3mqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:grabber" /></template>
