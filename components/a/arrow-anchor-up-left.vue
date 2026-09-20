<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt7-9wjst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bt7-9wjst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-anchor-up-left" /></template>
