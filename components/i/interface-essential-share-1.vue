<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz6iieisr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kz6iieisr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-share-1" /></template>
