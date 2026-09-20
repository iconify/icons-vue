<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbgqgkb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sbgqgkb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-above-outstretched-hand" /></template>
