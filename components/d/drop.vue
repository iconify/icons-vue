<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtd0qyxek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtd0qyxek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:drop" /></template>
