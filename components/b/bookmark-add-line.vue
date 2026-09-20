<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjhhhdbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjhhhdbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-add-line" /></template>
