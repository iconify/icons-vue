<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixwq2bc2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixwq2bc2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:angelscript" /></template>
