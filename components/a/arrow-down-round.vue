<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfbmzgbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfbmzgbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-round" /></template>
