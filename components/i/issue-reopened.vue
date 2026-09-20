<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzlx0ujqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="gzlx0ujqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-reopened" /></template>
