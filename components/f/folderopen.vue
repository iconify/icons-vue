<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y93-0lb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="y93-0lb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:folderopen" /></template>
