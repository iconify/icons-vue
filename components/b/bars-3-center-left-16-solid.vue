<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdo3n95-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wdo3n95-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-center-left-16-solid" /></template>
