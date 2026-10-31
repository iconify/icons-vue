<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-44zbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-44zbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-fill-round" /></template>
