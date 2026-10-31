<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxbmvbc7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxbmvbc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-plus-fill-round" /></template>
