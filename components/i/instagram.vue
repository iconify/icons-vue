<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xif1tcbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGRu6oNd6B" class="xif1tcbsa"/></defs><use href="#SVGRu6oNd6B"/><use href="#SVGRu6oNd6B"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:instagram" /></template>
