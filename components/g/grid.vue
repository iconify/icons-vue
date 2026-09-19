<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg7ftebsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg7ftebsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid" /></template>
