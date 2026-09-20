<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro38-jb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ro38-jb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:home-16" /></template>
