<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8o9vzk6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j8o9vzk6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:copy" /></template>
