<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al9eygyeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al9eygyeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-quote-close" /></template>
