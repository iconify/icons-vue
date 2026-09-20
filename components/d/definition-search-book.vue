<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6h3gr4bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z6h3gr4bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:definition-search-book" /></template>
