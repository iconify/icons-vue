<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_mj2m24j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z_mj2m24j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-link" /></template>
