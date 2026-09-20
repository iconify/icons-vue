<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uen8fg65q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uen8fg65q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-right-circle-filled" /></template>
