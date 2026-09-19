<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slcgjy_ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="slcgjy_ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hy" /></template>
