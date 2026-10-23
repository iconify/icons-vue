<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjop1kbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjop1kbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-indent-increase" /></template>
