<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf_g5ibkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_g5ibkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:macpaw" /></template>
