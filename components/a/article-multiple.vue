<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atzb4gb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atzb4gb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:article-multiple" /></template>
