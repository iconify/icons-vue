<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts_6gkbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ts_6gkbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-stackframe-dot" /></template>
