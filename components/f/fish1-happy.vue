<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u21022btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u21022btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish1-happy" /></template>
