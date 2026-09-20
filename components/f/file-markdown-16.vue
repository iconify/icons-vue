<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgglibcip.css';
import '../../css/o/op65_9z-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jgglibcip"/><path clip-rule="evenodd" class="op65_9z-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:file-markdown-16" /></template>
