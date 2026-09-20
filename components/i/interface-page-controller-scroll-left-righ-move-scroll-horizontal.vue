<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iil-_0epu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iil-_0epu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-page-controller-scroll-left-righ-move-scroll-horizontal" /></template>
