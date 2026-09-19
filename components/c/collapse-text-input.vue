<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je7ksxbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="je7ksxbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:collapse-text-input" /></template>
