<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crfaxib9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crfaxib9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:color-crayon" /></template>
