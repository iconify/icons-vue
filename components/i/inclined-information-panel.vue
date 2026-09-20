<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbg7o3_pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dbg7o3_pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:inclined-information-panel" /></template>
