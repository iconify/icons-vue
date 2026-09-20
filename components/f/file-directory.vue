<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysna8hi8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="ysna8hi8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory" /></template>
