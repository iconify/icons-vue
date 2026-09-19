<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsiui4qwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsiui4qwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-stroke-filled" /></template>
