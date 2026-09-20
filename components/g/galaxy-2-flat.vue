<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl8_wqbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hl8_wqbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:galaxy-2-flat" /></template>
