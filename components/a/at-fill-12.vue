<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry50nluez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ry50nluez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:at-fill-12" /></template>
