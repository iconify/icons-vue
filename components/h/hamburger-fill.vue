<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry1fr0bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry1fr0bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hamburger-fill" /></template>
