<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-3dycbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-3dycbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:diploma-scroll" /></template>
