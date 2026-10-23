<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1b17ybxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1b17ybxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bug-play" /></template>
