<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1dxpsbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n1dxpsbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:elevator" /></template>
