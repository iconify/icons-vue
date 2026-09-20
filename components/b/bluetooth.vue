<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcgiyscfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcgiyscfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bluetooth" /></template>
