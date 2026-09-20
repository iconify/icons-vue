<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yah-9lw2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yah-9lw2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:definition-search-book-remix" /></template>
