<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3-x1t1gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i3-x1t1gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:funnel-crossed-16" /></template>
