<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdnz6h9tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cdnz6h9tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:linked-database" /></template>
