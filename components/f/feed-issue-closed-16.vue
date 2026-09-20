<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jknpy-b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jknpy-b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-issue-closed-16" /></template>
