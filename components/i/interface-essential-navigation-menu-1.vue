<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx5d-4rvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sx5d-4rvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-navigation-menu-1" /></template>
