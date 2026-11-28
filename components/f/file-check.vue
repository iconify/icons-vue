<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5pdzxb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r5pdzxb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-check" /></template>
