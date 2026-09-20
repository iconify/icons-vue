<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxx19tb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lxx19tb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:braille-blind-solid" /></template>
