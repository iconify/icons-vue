<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px6ttq8id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px6ttq8id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:black-board-2-fill" /></template>
