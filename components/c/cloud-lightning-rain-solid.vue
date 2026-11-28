<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlxms-bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlxms-bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-lightning-rain-solid" /></template>
