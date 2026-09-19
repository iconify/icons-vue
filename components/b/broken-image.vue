<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no54uea3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="no54uea3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:broken-image" /></template>
