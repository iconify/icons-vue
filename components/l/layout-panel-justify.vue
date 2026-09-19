<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz6tltb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zz6tltb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-panel-justify" /></template>
