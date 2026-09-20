<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re9pfrb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="re9pfrb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:link-vertical" /></template>
