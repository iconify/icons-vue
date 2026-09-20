<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpi8iibkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpi8iibkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-wrench-outline" /></template>
