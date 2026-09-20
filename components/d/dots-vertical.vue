<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhv7v7_ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhv7v7_ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:dots-vertical" /></template>
