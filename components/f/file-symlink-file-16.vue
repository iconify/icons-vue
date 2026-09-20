<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmphkilgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tmphkilgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-symlink-file-16" /></template>
