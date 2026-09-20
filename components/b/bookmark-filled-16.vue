<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xworeqbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xworeqbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-filled-16" /></template>
