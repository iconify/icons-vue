<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve4etabbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve4etabbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-dot-corner-left-1-bold" /></template>
