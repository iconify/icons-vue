<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-v-b8bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-v-b8bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wiktionary" /></template>
