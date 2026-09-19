<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh3ujcu_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh3ujcu_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fox-news" /></template>
