<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx2q25b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dx2q25b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-under-taxi-checkerboard" /></template>
