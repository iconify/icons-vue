<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cklih1mfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cklih1mfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:blockquote-right" /></template>
