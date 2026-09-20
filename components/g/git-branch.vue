<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_1_-xmhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="s_1_-xmhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-branch" /></template>
