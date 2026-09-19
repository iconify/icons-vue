<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoqjnv0mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoqjnv0mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-square-rounded" /></template>
