<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r54_dtb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r54_dtb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:layers" /></template>
