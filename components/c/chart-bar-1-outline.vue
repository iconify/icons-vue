<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6z0wd76j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a6z0wd76j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-bar-1-outline" /></template>
