<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qemswebvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qemswebvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:download-outline" /></template>
