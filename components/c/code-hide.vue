<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyb2rnbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eyb2rnbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:code-hide" /></template>
