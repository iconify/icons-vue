<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0-79bbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j0-79bbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:grimace" /></template>
