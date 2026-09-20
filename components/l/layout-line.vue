<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiytj0umg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiytj0umg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-line" /></template>
