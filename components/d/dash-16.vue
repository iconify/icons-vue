<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhc7zy51m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xhc7zy51m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dash-16" /></template>
