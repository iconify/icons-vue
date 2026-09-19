<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w571e2b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w571e2b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:assembly-reference" /></template>
