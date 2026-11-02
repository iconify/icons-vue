<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7w878t9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7w878t9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-plus-line" /></template>
