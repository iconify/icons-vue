<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu62vb9be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu62vb9be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:clinic" /></template>
