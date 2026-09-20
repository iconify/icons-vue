<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq38ekbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wq38ekbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-ticket" /></template>
