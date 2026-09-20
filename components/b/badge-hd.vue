<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxab2u_no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxab2u_no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-hd" /></template>
