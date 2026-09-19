<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_zou2-zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="e_zou2-zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:egyptpyramid" /></template>
