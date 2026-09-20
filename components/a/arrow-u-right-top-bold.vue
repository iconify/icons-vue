<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqxtftbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqxtftbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-right-top-bold" /></template>
