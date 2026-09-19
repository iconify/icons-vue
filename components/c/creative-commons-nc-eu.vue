<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9adiubhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u9adiubhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons-nc-eu" /></template>
