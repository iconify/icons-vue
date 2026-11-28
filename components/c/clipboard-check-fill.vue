<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjg4y1s3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kjg4y1s3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clipboard-check-fill" /></template>
