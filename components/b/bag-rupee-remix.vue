<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djwb_fbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="djwb_fbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-rupee-remix" /></template>
