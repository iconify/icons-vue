<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3t2cs7_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c3t2cs7_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-md" /></template>
