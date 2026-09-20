<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3-nn-bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3-nn-bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bulletlist-sharp" /></template>
