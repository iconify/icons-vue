<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-x-swrga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d-x-swrga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:id-card-alt" /></template>
