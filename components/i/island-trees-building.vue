<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1ivbxbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z1ivbxbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:island-trees-building" /></template>
