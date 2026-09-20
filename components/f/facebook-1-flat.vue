<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxz7qzbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uxz7qzbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:facebook-1-flat" /></template>
