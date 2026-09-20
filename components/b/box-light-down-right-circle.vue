<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctet27sra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ctet27sra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-down-right-circle" /></template>
