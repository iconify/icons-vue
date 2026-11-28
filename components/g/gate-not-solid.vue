<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncwbxlk9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwbxlk9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-not-solid" /></template>
