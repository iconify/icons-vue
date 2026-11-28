<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yffa5ib7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yffa5ib7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:check-circle-multiple-thin" /></template>
