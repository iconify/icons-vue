<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywy51ebkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywy51ebkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:annotation-text" /></template>
