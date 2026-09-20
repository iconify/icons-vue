<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh0xbabcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh0xbabcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-personal-tag-outline" /></template>
