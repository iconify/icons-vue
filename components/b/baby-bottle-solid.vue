<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4_04ubwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4_04ubwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baby-bottle-solid" /></template>
