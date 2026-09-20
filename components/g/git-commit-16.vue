<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm0oa-gwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qm0oa-gwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-commit-16" /></template>
