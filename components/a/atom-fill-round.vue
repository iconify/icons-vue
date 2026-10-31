<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xebxaj5gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xebxaj5gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atom-fill-round" /></template>
