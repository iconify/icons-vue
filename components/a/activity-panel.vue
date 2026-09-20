<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c71yqfbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c71yqfbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:activity-panel" /></template>
