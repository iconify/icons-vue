<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_9sgmbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s_9sgmbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:bell" /></template>
