<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oggwidboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oggwidboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-zoom-out-page" /></template>
