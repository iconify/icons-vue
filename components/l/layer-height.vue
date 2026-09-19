<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bst88j9io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bst88j9io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-height" /></template>
