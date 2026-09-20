<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reqybcxbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="reqybcxbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-mp4-outline" /></template>
