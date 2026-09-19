<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7ku-vbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="o7ku-vbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:document-search-fill-12" /></template>
