<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yksjou5qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="yksjou5qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:list-ordered" /></template>
