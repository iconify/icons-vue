<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zshbt6bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zshbt6bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:carousel-h-filled" /></template>
