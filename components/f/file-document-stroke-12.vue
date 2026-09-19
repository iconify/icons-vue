<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suhh-xi_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="suhh-xi_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-document-stroke-12" /></template>
