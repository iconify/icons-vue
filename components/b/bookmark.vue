<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7ll9vpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="sx7ll9vpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bookmark" /></template>
