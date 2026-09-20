<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znh6ruuii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="znh6ruuii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-solid" /></template>
