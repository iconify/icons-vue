<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzpi8mbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzpi8mbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:eclipse" /></template>
