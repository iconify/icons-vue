<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpm_1gptr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wpm_1gptr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-discussion-16" /></template>
