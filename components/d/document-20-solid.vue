<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-m54achm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i-m54achm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-20-solid" /></template>
