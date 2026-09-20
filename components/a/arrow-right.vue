<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyos_vo5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dyos_vo5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-right" /></template>
