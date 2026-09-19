<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja2ive0mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ja2ive0mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:check-all" /></template>
