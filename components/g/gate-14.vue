<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za6dc3b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="za6dc3b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:gate-14" /></template>
