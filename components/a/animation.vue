<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5xjlxhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy5xjlxhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:animation" /></template>
