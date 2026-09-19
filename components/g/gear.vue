<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry1z8robp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry1z8robp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:gear" /></template>
