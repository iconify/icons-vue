<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnq287bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnq287bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:frame-alt-empty" /></template>
