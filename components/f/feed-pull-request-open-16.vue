<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnpqf24zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mnpqf24zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-pull-request-open-16" /></template>
