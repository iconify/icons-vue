<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upjz_j38p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="upjz_j38p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:libreoffice" /></template>
