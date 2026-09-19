<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3u6ra6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co3u6ra6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:invoice-filled" /></template>
