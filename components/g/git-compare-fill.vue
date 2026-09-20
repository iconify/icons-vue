<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2oymvbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2oymvbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-compare-fill" /></template>
