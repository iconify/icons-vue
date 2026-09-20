<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv_45objh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fv_45objh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-remix" /></template>
