<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxmzf6d8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uxmzf6d8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:file-edit" /></template>
