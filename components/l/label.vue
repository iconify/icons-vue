<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luio64b5z.css';
import '../../css/j/j6ei9utzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="luio64b5z"/><path class="j6ei9utzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:label" /></template>
