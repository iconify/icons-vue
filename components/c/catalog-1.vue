<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-mrcre1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-mrcre1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:catalog-1" /></template>
