<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odc5s1qbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odc5s1qbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:home" /></template>
