<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6e8nvbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6e8nvbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:home-solid" /></template>
