<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxpizu1yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bxpizu1yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-mov-outline" /></template>
