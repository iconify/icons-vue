<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqhfjacho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yqhfjacho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-public-health-center" /></template>
