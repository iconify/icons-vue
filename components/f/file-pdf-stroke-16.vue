<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1kw-cc7c.css';
import '../../css/o/odgrbee8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1kw-cc7c"/><rect class="odgrbee8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-pdf-stroke-16" /></template>
