<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-1-nhi8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-1-nhi8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-plus-fill-round" /></template>
