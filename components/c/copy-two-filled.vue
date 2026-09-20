<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkav4jb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zkav4jb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:copy-two-filled" /></template>
