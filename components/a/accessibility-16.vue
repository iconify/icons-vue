<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyel8tbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yyel8tbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:accessibility-16" /></template>
