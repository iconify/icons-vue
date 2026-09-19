<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zttcs3bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zttcs3bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-pen" /></template>
