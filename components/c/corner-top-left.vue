<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke0_784jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ke0_784jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:corner-top-left" /></template>
