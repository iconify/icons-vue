<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3g4u7q3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3g4u7q3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-ranslation-1" /></template>
