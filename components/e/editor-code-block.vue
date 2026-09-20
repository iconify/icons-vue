<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xza3v1tkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xza3v1tkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-code-block" /></template>
