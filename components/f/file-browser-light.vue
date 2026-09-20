<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrhpp6bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nrhpp6bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-browser-light" /></template>
