<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtfdtoen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtfdtoen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:japanese-rectangle-filled" /></template>
