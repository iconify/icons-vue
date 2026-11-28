<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcfv2bbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcfv2bbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:line-dashed-solid" /></template>
