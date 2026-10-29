<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwlmofepp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwlmofepp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-left-solid" /></template>
