<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d61kb7bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d61kb7bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:diagonal-arrow-left-down-outline" /></template>
