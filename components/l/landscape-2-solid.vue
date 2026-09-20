<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu_xpzb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tu_xpzb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:landscape-2-solid" /></template>
