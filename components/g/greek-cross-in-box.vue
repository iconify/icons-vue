<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx588wb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xx588wb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:greek-cross-in-box" /></template>
