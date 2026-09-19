<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjkdamf3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xjkdamf3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:goods" /></template>
