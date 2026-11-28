<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh9jewipe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh9jewipe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-git-solid" /></template>
