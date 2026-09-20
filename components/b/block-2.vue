<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7-fi2btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f7-fi2btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:block-2" /></template>
