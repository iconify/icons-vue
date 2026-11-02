<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc9yfib9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc9yfib9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-git-fill" /></template>
