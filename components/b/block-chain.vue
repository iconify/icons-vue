<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0_-kgbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0_-kgbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:block-chain" /></template>
