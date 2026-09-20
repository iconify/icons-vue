<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zydi13njm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zydi13njm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:avatar" /></template>
