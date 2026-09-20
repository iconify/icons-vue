<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoj4kmq1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uoj4kmq1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-note-book" /></template>
