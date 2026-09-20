<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evc3-36gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="evc3-36gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-issue-draft-16" /></template>
