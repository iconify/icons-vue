<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a68wrvb8b.css';
import '../../css/g/g5xqtsbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a68wrvb8b"/><path class="g5xqtsbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bookmark-add" /></template>
