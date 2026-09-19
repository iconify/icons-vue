<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjhzgobae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjhzgobae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:inbox" /></template>
