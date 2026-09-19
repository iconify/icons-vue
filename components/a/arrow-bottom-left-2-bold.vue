<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkvedyb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkvedyb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-2-bold" /></template>
