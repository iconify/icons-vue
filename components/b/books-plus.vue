<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0bdxl2ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0bdxl2ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:books-plus" /></template>
