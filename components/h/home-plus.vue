<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txm3c8rvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txm3c8rvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:home-plus" /></template>
