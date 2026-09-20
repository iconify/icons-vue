<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwcs5xqli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwcs5xqli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-to-dot" /></template>
