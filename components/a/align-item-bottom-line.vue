<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdx309bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdx309bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:align-item-bottom-line" /></template>
