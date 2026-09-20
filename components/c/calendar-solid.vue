<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt3uk3bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt3uk3bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-solid" /></template>
