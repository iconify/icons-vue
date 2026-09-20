<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz7-w4vmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz7-w4vmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:magnify" /></template>
