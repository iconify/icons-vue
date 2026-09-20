<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo98b5gqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo98b5gqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-left-line" /></template>
