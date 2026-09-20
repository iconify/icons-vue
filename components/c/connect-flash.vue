<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiv1_8bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yiv1_8bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:connect-flash" /></template>
