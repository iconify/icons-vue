<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd_3jgbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd_3jgbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-out" /></template>
