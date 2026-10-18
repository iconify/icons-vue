<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybu_i-bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu_i-bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bot-message-square" /></template>
