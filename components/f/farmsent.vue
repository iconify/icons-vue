<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl8ogjbin.css';
import '../../css/v/vbn5-wb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1440,"height":810};
const content = `<defs><clipPath id="SVG6nCoMc7C"><path class="zl8ogjbin"/></clipPath></defs><g clip-path="url(#SVG6nCoMc7C)"><path class="vbn5-wb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:farmsent" /></template>
