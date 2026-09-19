<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjamiqbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zjamiqbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:arrow-alt-circle-down" /></template>
