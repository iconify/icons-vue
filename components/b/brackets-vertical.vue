<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja0nf1bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ja0nf1bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:brackets-vertical" /></template>
