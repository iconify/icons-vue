<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2ce9acfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a2ce9acfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:angles-down" /></template>
