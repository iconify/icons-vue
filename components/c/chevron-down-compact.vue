<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjlsuub8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yjlsuub8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chevron-down-compact" /></template>
