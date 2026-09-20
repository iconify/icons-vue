<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhnqpabwu.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":375,"height":375};
const content = `<defs><path id="SVGdOj2Ibak" class="nhnqpabwu"/></defs><use href="#SVGdOj2Ibak" class="d2kvgvbvc"/><use href="#SVGdOj2Ibak" class="d2kvgvbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:glincker" /></template>
