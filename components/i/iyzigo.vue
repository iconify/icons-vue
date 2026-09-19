<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjfkgfbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="pjfkgfbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:iyzigo" /></template>
