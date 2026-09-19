<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo4avb77y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1280};
const content = `<g transform="translate(0 1280) scale(1 -1)"><path class="bo4avb77y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:angle-double-down" /></template>
