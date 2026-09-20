<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvap_sbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wvap_sbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:elementor" /></template>
