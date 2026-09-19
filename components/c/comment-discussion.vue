<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln3zthrqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ln3zthrqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:comment-discussion" /></template>
