<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af5zxacjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="af5zxacjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:color-swatches-solid" /></template>
