<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1b_yxnqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1b_yxnqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beanie-filled" /></template>
