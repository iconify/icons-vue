<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7qowt6cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7qowt6cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-arrow-down-line" /></template>
