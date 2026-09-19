<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my5n0s3xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="my5n0s3xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:interface-definition-alt" /></template>
