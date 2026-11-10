<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb1x9obgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wb1x9obgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-arrow-path-20-solid" /></template>
