<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnar4sbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnar4sbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:linkvertise" /></template>
