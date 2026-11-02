<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo1jr6bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo1jr6bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-2-line" /></template>
