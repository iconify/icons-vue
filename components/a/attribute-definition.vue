<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb8ibbc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pb8ibbc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:attribute-definition" /></template>
