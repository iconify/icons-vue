<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1e0kbbst.css';
import '../../css/y/yu8tkqs3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="o1e0kbbst"/><path class="yu8tkqs3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dark-skin-tone" /></template>
