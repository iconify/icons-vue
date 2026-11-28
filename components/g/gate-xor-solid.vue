<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypwpt66ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypwpt66ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-xor-solid" /></template>
