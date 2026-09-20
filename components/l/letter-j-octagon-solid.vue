<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu-8o6bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu-8o6bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j-octagon-solid" /></template>
