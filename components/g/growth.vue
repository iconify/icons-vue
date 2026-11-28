<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5900e9gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5900e9gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:growth" /></template>
