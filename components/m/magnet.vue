<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4waorgjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="z4waorgjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:magnet" /></template>
