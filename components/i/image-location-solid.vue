<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7snm4f3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r7snm4f3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:image-location-solid" /></template>
