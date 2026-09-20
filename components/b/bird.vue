<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2et42jeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="k2et42jeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bird" /></template>
