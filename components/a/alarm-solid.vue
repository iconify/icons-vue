<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw_mxsb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_mxsb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-solid" /></template>
