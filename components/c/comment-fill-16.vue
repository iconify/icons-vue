<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwl5agbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kwl5agbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-fill-16" /></template>
