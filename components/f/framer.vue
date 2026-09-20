<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpk25w8xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpk25w8xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:framer" /></template>
