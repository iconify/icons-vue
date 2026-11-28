<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djqr_wbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djqr_wbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:image-lock" /></template>
