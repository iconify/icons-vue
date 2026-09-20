<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td4f8bzwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td4f8bzwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:highlighter" /></template>
