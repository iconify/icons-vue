<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsk7q2blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tsk7q2blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-issue-reopen-16" /></template>
