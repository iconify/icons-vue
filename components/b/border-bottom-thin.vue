<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amns3_b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="amns3_b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-bottom-thin" /></template>
