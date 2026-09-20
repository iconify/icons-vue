<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmoklgqjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmoklgqjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-square" /></template>
