<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy-kdob5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy-kdob5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-fill-round" /></template>
