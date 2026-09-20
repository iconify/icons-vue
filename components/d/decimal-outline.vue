<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo3u2n3vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zo3u2n3vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:decimal-outline" /></template>
