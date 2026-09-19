<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiqsblbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiqsblbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:hard-hat" /></template>
