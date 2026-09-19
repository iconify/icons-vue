<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs0o44c0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fs0o44c0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:elevator" /></template>
