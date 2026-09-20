<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cea3snb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cea3snb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bitcomet" /></template>
