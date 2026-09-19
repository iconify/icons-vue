<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6yj0kbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6yj0kbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:chat-1" /></template>
