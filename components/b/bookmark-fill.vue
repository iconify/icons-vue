<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmlzz4jlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmlzz4jlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bookmark-fill" /></template>
