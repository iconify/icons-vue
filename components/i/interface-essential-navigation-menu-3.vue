<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmo_ecbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fmo_ecbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-navigation-menu-3" /></template>
