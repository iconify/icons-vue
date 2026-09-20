<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbrxdcbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrxdcbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-float-left" /></template>
