<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrcby-4rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrcby-4rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-search" /></template>
