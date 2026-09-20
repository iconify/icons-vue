<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vec1kpb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vec1kpb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:fingerprint-1" /></template>
