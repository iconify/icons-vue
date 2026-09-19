<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zua73sfyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zua73sfyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hugeicons" /></template>
