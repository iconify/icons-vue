<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4hs8gbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a4hs8gbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:folder-compact" /></template>
