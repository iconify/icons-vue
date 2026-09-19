<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqjkksdmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="vqjkksdmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:list-2" /></template>
