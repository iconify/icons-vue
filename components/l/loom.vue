<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edgr19bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="edgr19bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:loom" /></template>
