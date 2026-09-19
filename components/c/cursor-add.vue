<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j62ez0b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j62ez0b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-add" /></template>
