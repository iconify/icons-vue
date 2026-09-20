<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzeumybvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzeumybvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-slack-solid" /></template>
