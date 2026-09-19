<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpcbqabtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpcbqabtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bookmark" /></template>
