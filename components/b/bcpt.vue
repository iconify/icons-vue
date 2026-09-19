<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwcf03b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jwcf03b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bcpt" /></template>
