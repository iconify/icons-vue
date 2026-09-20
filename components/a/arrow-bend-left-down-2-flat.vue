<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp_c66vkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hp_c66vkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-bend-left-down-2-flat" /></template>
