<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cakywobim.css';
import '../../css/i/iz024ebeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cakywobim"/><path clip-rule="evenodd" class="iz024ebeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:back-square-filled" /></template>
