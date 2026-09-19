<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2mpnnbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1824,"height":1824};
const content = `<path class="v2mpnnbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:kanji-yubi" /></template>
