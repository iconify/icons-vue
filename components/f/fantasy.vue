<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlughgcxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xlughgcxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:fantasy" /></template>
