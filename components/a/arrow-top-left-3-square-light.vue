<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl4i9x41k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl4i9x41k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-3-square-light" /></template>
