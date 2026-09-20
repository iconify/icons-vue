<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvrky_bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yvrky_bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:grid" /></template>
