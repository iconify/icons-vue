<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbd4s_mlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbd4s_mlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-align-top" /></template>
