<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3_nbdb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3_nbdb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-box-outline-blank" /></template>
