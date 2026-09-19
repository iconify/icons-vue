<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de0ny6bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="de0ny6bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:arrowdown" /></template>
