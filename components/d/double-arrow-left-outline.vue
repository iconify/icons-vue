<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knz6qdp8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="knz6qdp8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:double-arrow-left-outline" /></template>
