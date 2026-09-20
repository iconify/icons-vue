<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnqdxxbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnqdxxbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-sun-rain-solid" /></template>
