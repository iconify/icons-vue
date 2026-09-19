<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fitr7gb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fitr7gb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlenine" /></template>
