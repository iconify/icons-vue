<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whtqf2epm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whtqf2epm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:key" /></template>
