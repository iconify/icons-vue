<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v58p9ubwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v58p9ubwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:magnet-up-fill" /></template>
