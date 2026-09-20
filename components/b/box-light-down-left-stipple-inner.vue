<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-__6xbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="b-__6xbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-down-left-stipple-inner" /></template>
