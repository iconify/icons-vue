<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1e30abbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s1e30abbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:mail-plus" /></template>
