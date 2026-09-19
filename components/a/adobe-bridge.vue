<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuwx2ibae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuwx2ibae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-bridge" /></template>
