<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjw4l9poi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjw4l9poi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:live-blog-light" /></template>
