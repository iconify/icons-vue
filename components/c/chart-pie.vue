<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlzq5sxjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlzq5sxjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pie" /></template>
