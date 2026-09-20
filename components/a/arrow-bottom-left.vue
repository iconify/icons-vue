<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvntz0b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cvntz0b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-bottom-left" /></template>
