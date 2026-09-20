<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uckz_1f4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uckz_1f4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-navigation-left-circle-2" /></template>
