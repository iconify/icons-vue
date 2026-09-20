<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drqgfb63j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="drqgfb63j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:batch-add-filled" /></template>
