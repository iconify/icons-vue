<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfad_mbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfad_mbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:atom" /></template>
