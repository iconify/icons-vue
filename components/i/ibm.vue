<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2zosibgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b d2zosibgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:ibm" /></template>
