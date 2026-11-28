<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbly7ysou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbly7ysou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:line-height-solid" /></template>
