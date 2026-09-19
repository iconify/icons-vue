<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4qbkmbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f4qbkmbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:file-video" /></template>
