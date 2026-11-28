<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywaur6b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywaur6b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:input-x" /></template>
