<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgm26p3ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgm26p3ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:barcode-2" /></template>
