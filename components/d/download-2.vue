<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5j_e6bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d5j_e6bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:download-2" /></template>
