<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kot-p6b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kot-p6b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:chat-2" /></template>
