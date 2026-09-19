<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpp35q0pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpp35q0pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:apple-imac-2021-side" /></template>
