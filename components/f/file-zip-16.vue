<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox4mohbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ox4mohbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-zip-16" /></template>
