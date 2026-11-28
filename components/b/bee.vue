<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amhv56bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="amhv56bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bee" /></template>
