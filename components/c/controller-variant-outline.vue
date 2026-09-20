<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsnapl6dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsnapl6dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-variant-outline" /></template>
