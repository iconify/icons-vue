<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjzdncbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjzdncbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-and-solid" /></template>
