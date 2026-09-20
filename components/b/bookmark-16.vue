<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe7c8fl3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qe7c8fl3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-16" /></template>
