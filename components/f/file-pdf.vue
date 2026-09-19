<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phrv23brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phrv23brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-pdf" /></template>
