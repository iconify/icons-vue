<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkqn_-bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bkqn_-bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-beside-conifer-tree-above-water" /></template>
