<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmd1qmb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmd1qmb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:landscape-line" /></template>
