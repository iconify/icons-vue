<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqto7nzoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqto7nzoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:line-height-fill-round" /></template>
