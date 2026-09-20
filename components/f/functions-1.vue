<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzuwc8bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzuwc8bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:functions-1" /></template>
