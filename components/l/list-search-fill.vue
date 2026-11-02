<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1jjywnlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jjywnlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-search-fill" /></template>
