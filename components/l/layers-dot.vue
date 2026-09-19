<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjj249buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xjj249buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layers-dot" /></template>
