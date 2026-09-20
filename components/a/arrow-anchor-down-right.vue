<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1yxwjbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q1yxwjbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-anchor-down-right" /></template>
