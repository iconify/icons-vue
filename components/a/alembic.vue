<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-7avmboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-7avmboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:alembic" /></template>
