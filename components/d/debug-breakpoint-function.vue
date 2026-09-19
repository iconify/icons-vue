<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg4oyd4_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bg4oyd4_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-function" /></template>
