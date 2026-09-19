<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0nipdbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0nipdbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:flip-2-outline" /></template>
