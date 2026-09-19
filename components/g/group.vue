<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfpjty8ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1792};
const content = `<path class="bfpjty8ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:group" /></template>
