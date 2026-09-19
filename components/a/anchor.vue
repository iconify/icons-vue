<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvltm58kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="cvltm58kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:anchor" /></template>
