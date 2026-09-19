<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnvh5fb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gnvh5fb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:comment-slash" /></template>
