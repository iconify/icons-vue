<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwuu6zh6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qwuu6zh6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bookmark-filled-16" /></template>
