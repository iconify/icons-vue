<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs-wccbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs-wccbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:contacts-round" /></template>
