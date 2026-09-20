<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgkw-vbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hgkw-vbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:low-shrub" /></template>
