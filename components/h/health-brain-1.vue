<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-t2sub4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-t2sub4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-brain-1" /></template>
