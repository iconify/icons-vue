<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl3x9zbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":480};
const content = `<path class="nl3x9zbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:link" /></template>
