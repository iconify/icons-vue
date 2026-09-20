<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruon_hbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ruon_hbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-information-circle-2" /></template>
