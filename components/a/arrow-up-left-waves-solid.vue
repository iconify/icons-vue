<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwqfbdcyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwqfbdcyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-left-waves-solid" /></template>
