<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7jiv7qer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7jiv7qer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff-multiple" /></template>
