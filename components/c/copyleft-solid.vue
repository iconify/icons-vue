<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc-3cybbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc-3cybbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:copyleft-solid" /></template>
