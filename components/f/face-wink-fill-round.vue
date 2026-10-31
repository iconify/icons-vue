<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxf3dbcsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxf3dbcsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-wink-fill-round" /></template>
