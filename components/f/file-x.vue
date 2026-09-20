<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyd83wisg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyd83wisg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file-x" /></template>
