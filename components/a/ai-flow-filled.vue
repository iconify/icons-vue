<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vszaobclx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vszaobclx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ai-flow-filled" /></template>
