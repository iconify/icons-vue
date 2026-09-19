<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_md5nbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j_md5nbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightbulb-fill-16" /></template>
